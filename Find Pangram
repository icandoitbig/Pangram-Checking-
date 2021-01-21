func findPragram(test text: String) {
    var capSet = Set<Int>()
    
    for i in text {
        if let asciiValue = i.asciiValue {
            switch asciiValue {
            case 65..<91:
                capSet.insert( Int(asciiValue - 65))
            case 97..<123 :
                capSet.insert(Int(asciiValue - 97))
            default:
                continue
            }
        }
    }
    print(capSet.count > 25 ? "is pragram" : "not pragram")
}
