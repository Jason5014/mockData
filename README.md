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
      uid: '123',
      company: '公司',
      name: '姓名',
      IDNumber: '证件号',
      phone: '手机号‘
    },
    ...
  ]
}
```
