package Model;

public class MemberList
{
    private static String memberListName[];
    private static String memberListDate[];
    private static String memberListHours[];
    private static String memberList[][];
    
    public void setMemberListName(String memberListName[])
    {
        MemberList.memberListName = memberListName;
    }
    
    public void setMemberListDate(String memberListDate[])
    {
        MemberList.memberListDate = memberListDate;
    }
    
    public void setMemberListHours(String memberListHours[])
    {
        MemberList.memberListHours = memberListHours;
    }
    
    public void setMemberList(String memberList[][])
    {
        MemberList.memberList = memberList;
    }
    
    public String[] getMemberListName()
    {
        return MemberList.memberListName;
    }
    
    public String[] getMemberListDate()
    {
        return MemberList.memberListDate;
    }
    
    public String[] getMemberListHours()
    {
        return MemberList.memberListHours;
    }
    
    public String[][] getMemberList()
    {
        return MemberList.memberList;
    }
    
}
