class Solution:
    def reverseStr(self, s: str, k: int) -> str:
        out=''
        for i in range(0,len(s),2*k):
            out=out+s[i:i+k][::-1]+s[i+k:i+2*k]
        return out
