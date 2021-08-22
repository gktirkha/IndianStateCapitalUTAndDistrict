# IndianStateCapitalUTAndDistrict
This JSON File Contains List Of All Indian State With Their Capitals And District List
Source http://districts.nic.in/
**structure:-**
{
    key("states"):(JSONArray) [
        {
            key ("state"):"String",
            key ("capital"):"String",
            key ("districts"):JSON Array[
            //contains the list of district eg:- 
              "district 1"
              "district 2"
              .
              .
              .
              "district n"
            ]
        }
    ]
}
