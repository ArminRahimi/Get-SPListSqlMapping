# Get-SPListSqlMapping

Retrieve SQL storage mapping (ColName) for SharePoint Server Lists.

Developed by DEXIRO

---

## Features

- Supports SharePoint Server 2016 / 2019
- Reads SharePoint List Fields
- Retrieves SQL Storage Column
- Uses .NET Reflection
- No SQL queries required
- Displays:
    - Display Name
    - Internal Name
    - SQL Column
    - Field Type

---

## Screenshot



---

## Usage

Run SharePoint Management Shell as Administrator.

```powershell
.\Get-SPListSqlMapping.ps1
```

Enter:

- Site URL
- List Name

Example

```
Site URL:
http://portal.group.local/PMO

List:
Meeting
```

Output

|Display Name|Internal Name|SQL Column|
|------------|-------------|----------|
|Title|Title|nvarchar1|
|Organizer|Organizer|int1|
|Description|Description|ntext2|

---

## Requirements

- SharePoint Server 2016/2019
- SharePoint Management Shell
- Farm Administrator

---

## License

MIT License

---

Developed by DEXIRO

https://DEXIRO.ir
