| Column      | Type            | Mô tả |

| ----------- | --------------- | ----- |

| BrandID     | BIGINT IDENTITY | PK    |

| BrandCode   | VARCHAR(20)     | BR001 |

| BrandName   | NVARCHAR(100)   | Apple |

| Description | NVARCHAR(255)   |       |

| Status      | BIT             |       |

| CreatedAt   | DATETIME2       |       |

| UpdatedAt   | DATETIME2       |       |

Business Rule



BrandName không được trùng.

Không xóa Brand nếu đang có Product.

