# CadastroDeFuncionarios

Vá ao program.cs.<br>
Inclua o seu login de conexão do SQL server.<br>
Altere o nome do banco de dado.<br><br>

// Add services to the container.
            builder.Services.AddControllersWithViews();
            builder.Services.AddDbContext<EmployeeContext>(options => options.UseSqlServer("Server=SuaConexao;Database=NomeDoBancoDeDados;Trusted_Connection=True;"));

            var app = builder.Build();
