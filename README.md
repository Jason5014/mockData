# mockData
a repository to mock data

### route

#### /jason5014/mockdata/getWorkflowCustomSearchData
海太访客流程智能输入搜索请求
- method: get
- params: company, dept | name, dept
```
{ company: 公司, dept: 12 }
或者 { name: 名称, dept: 23 }
```
- returns:
```
{
  data: [
    {
      company: 公司
      position: 职务
      name: 姓名
      IDType: 证件类型
      IDNumber: 证件号
      ...
    },
    ...
  ]
}
```
