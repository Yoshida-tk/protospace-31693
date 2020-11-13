| _usersテーブル_                 |
|                                |
| email (string型, NOT NULL)     |
| password (string型, NOT NULL)  |
| name (string型, NOT NULL)      |
| profile (text型, NOT NULL)     |
| position (text型, NOT NULL)    |

| _prototypesテーブル_            |
|                               |
| title (string型, NOT NULL)    |
| catch_copy (text型, NOT NULL) |
| concept (text型, NOT NULL)    |
| image (ActiveStorageで実装)    |
| user (references型)           |

| _commentsテーブル_              |
|                                |
| text (text型, NOT NULL)        |
| user (references型)            |
| prototype (references型)       |

