# vowel_remove_str
Remove vowel from string using Python
def removeVowels(str):
    new_str = ""
    for char in str:    
        if char not in ('a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U'):
            new_str = new_str + char
    return new_str
string_example = "The quick brown fox jumps over the lazy dog"
print(removeVowels(string_example))
