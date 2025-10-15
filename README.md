```mermaid
flowchart TB
    %% Headquarters
    A[Headquarters\nGlobal Business Division\nDivision Manager: ExecutiveName]

    %% HQ Management
    A --> B1[EU Region HQ\nManager: Umezu Koji]
    A --> B2[EU Region HQ\nManager: Shinano Takayoshi]
    A --> B3[EU Region HQ\nSub-Manager: Yagi Shohei]

    %% L1 Groups
    A --> C1[Global Store Mgmt (GX)\nChief: Sonehara Yosuke]
    A --> C2[Global Customer Service (GCS)\nChief: Sonehara Yosuke]
    A --> C3[Global Biz Sales (GBS)\nChief: Hanaoka Ryu]

    %% L2 GCS Subgroup
    C2 --> D1[GCS Subgroup\nSub-Chief: Yukako Sashihata]

    %% GCS Crew
    D1 --> E1[Zheng Boyu]
    D1 --> E2[Yamaguchi Satoshi]
    D1 --> E3[Miyazawa Yuri]
    D1 --> E4[Iijima Sachiko]
    D1 --> E5[Kitamura Futana]
    D1 --> E6[Hachiya Ryo]
    D1 --> E7[Segami Yuko]
    D1 --> E8[Kikuchi Ryo]
    D1 --> E9[Narita Tomoko]
    D1 --> E10[West Tamaki MacDominic]
    D1 --> E11[Kimura Keiko]
    D1 --> E12[Anzai Aya]
    D1 --> E13[Clowry Chika]
    D1 --> E14[Yamamoto Gabe Yoko]
    D1 --> E15[Ishikawa Kana]

    %% L2 GBS Subgroup
    C3 --> D2[GBS Subgroup\nSub-Chief: Daichi Yoshida]

    %% International Offices
    A --> F1[GCS (HK)\nChief: Qu Jia Ting AK]
    A --> F2[GCS (VN)\nStaff Member: Tran Phuoc An]
    A --> F3[GCS (VN)\nStaff Member: Ton That Bao Tam]
