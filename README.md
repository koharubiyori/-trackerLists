## TrackerListsBale

In many BT clients, the subscription source for tracker lists is typically limited to just one. This can be very frustrating when you try to merge lists from multiple sources. 
However, by using the following URL, you can combine URLs from multiple sources into one, and the final tracker list will automatically remove duplicates.

> https://tracker-lists.koharu.top

## Parameters

If `reset` parameter is not provided, the subscription sources in the project's [list.txt](https://github.com/koharubiyori/TrackerListsBale/blob/master/list.txt) file will be used by default.

* `divider`: The split character between returned tracker list. The default is newline(`\n`)
* `append`: Subscription sources to be appended, splited by commas(`,`) between source URLs
* `reset`: This replaces the subscription sources in the `list.txt` file, that splited by commas(`,`) in the same way
