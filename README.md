flowchart LR
  IK["İK Sorumlusu"]
  Mudur["İK Müdürü"]
  Admin["Admin"]
  subgraph S["İK Yönetim Sistemi"]
    UC(["Kadro listesini görüntüle"])
  end
  IK --- UC
  Mudur --- UC
  Admin --- UC
