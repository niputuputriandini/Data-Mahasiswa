# Data-Mahasiswa
CREATE TABLE [dbo].[mahasiswa](
	[nim] [char](10) NOT NULL,
	[nama] [varchar](50) NULL,
	[tgllahir] [date] NULL,
	[tmplahir] [varchar](50) NULL,
	[kodejurusan] [char](2) NOT NULL,
 CONSTRAINT [PK_mahasiswa] PRIMARY KEY CLUSTERED 
(
	[nim] ASC
)WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON) ON [PRIMARY]
) ON [PRIMARY]
