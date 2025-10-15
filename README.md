flowchart TB
    %% 事業本部
    A[事業本部\nGlobal Business Division\nDivision Manager：ExecutiveName]

    %% HQ MGT
    A --> B1[EU Region HQ\nEUリージョン本部\nManager：梅津 幸司（兼任）]
    A --> B2[EU Region HQ\nEUリージョン本部\nManager：信濃 孝喜（兼任）]
    A --> B3[EU Region HQ\nEUリージョン本部\nSub-Manager：八木 翔平（HQ兼任）]

    %% L1 グループ
    A --> C1[Global Store Mgmt (GX)\nChief：曽根原 洋介（GCS兼任）]
    A --> C2[Global Customer Service (GCS)\nChief：曽根原 洋介（主担当）]
    A --> C3[Global Biz Sales (GBS)\nChief：花岡 龍（主担当）]

    %% L2 GCS サブグループ
    C2 --> D1[GCS サブグループ\nSub-Chief：指籏 由香子]

    %% GCS Crew
    D1 --> E1[鄭 博予]
    D1 --> E2[山口 智]
    D1 --> E3[宮澤 侑里]
    D1 --> E4[飯島 幸子]
    D1 --> E5[北村 双菜]
    D1 --> E6[蜂谷 遼]
    D1 --> E7[瀬上 緩子]
    D1 --> E8[菊池 諒]
    D1 --> E9[成田 知子]
    D1 --> E10[ウエストタマキ マックドミニク]
    D1 --> E11[木村 恵子]
    D1 --> E12[安齊 綾]
    D1 --> E13[クローリー 知佳]
    D1 --> E14[山本ゲープ 容子]
    D1 --> E15[石川 佳菜]

    %% L2 GBS サブグループ
    C3 --> D2[GBS サブグループ\nSub-Chief：吉田 大地]

    %% 国際拠点
    A --> F1[GCS (HK)\nChief：區家挺 AK（Webike HK）]
    A --> F2[GCS (VN)\nStaff Member：Trần Phước An（Webike Vietnam）]
    A --> F3[GCS (VN)\nStaff Member：Tôn Thất Bảo Tâm（Webike Vietnam）]
