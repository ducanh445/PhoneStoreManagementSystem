| Column       | Type          |

| ------------ | ------------- |

| EmployeeID   | BIGINT        |

| EmployeeCode | VARCHAR(20)   |

| FullName     | NVARCHAR(100) |

| Gender       | BIT           |

| DateOfBirth  | DATE          |

| Phone        | VARCHAR(15)   |

| Email        | VARCHAR(100)  |

| Address      | NVARCHAR(255) |

| HireDate     | DATE          |

| Salary       | DECIMAL(18,2) |

| StoreID      | BIGINT        |

| Status       | BIT           |

| CreatedAt    | DATETIME2     |

| UpdatedAt    | DATETIME2     |
FK:
StoreID



↓



Store

Business Rule



Email không trùng

Phone không trùng

EmployeeCode không trùng

