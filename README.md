# Mermaidtest

gantt
  Completed task :crit, done,    t1, 2022-01-03, 3d
  Active task    :      active,  t2, after t1,   3d
  Future task    :               t3, after t2,   5d
  Future task2   :                               3d

flowchart TD
  START-->A{アントニオ?}
  A-->|Yes|猪木
  A-->|No|B{アントキノ?}
    B-->|Yes|猪木
    B-->|No|END

sequenceDiagram
  autonumber
  Client->>+Server: GET /issues
  Server-->>-Client: response

sequenceDiagram
  actor User
  User ->> モニター: 暗証番号を入力