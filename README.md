# Programa-de-leitura-de-senha
 class Program
    {
        static void Main(string[] args)
        {
            int senha = 0; // variável para armazenar a senha digitada pelo usuário

            // Loop que lê a senha repetidamente até ela ser correta
            while (senha != 141119)
            {
                Console.Write("Digite a senha: ");
                senha = int.Parse(Console.ReadLine());

                if (senha != 141119)
                {
                    Console.WriteLine("Senha Invalida");
                }
            }

            // Mensagem de Acesso Permitido
            Console.WriteLine("Acesso Permitido");
        }
    }
}
