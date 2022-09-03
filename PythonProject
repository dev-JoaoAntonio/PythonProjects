
CHAVE_API = '***'

bot = telebot.TeleBot(CHAVE_API)


@bot.message_handler(commands=['Python'])
def python(mensagem_padrao):
    bot.reply_to(mensagem_padrao, 'Com diversos cursos feitos durante sua carreira, dev_JoãoAntônio tem, além de 6 meses feitos durante'
                                  ' a sua formação em ciências da computação, que eram focados no aprendizado de python, foram dedicadas'
                                  ' mais de 120 horas em cursos criados apenas para o aprendizado de python. Durante sua jornada na'
                                  ' programação, diversos trabalho surgiram, e não só como forma de trabalhar e ganhar dinheiro,'
                                  ' mas também como forma de aprendizado, garantindo experiências únicas e uma boa reputação dentro do meio, tendo'
                                  ' em vista que são poucos aqueles que trabalham em diversos projetos remunerados, com tanta dedicação e'
                                  ' vontade.. Sua paixão por criar aquilo que vem a mente garantiu à João o amor pela busca e pesquisa,'
                                  ' uma vez que este está em constante aprimoramento, já que não recusa desafios dentro da programação,'
                                  ' dessa forma, a oportunidade  do "querer aprender" cada vez mais surge incontávelmente, atribuindo à'
                                  ' João Antônio uma habilidade dificilmente encontrada no mercado hoje, a produtividade, habilidade e'
                                  ' expertise em seus trabalhos. Caso queira verificar ceritificados de aprendizagem, basta clicar na'
                                  ' mensagem com o link abaixo!')

@bot.message_handler(commands=['JavaScript'])
def python(mensagem_padrao):
    bot.reply_to(mensagem_padrao,'...')

@bot.message_handler(commands=['HTML'])
def python(mensagem_padrao):
    bot.reply_to(mensagem_padrao,'O deisgn sempre foi uma habilidade marcante em João, já que trabalhou com design gráfico'
                                 'no passado. Logo, após se descobrir apaixonado pelo mundo da programação, o trabalho com o front-end '
                                 'ofereceu-lhe um foco a mais, contudo, para que desenvolvesse seus próprios projetos, além do trabalho, '
                                 'foi necessário o aprendizado do back-end, e lá, em pouco tempo descobrindo o HTML,que João se viu '
                                 'produzindo o código de sites que o deixava entusiasmado em produzir mais. Foram dias e dias olhando '
                                 'códigos de sites que todos conhecemos, tais como google, youtube, whattsapp, apenas por curiosidade'
                                 'e foi assim que João se tornou um entusiasta pela produção de sites. Para alguém que sempre esteve inserido '
                                 'no mundo da computação, passar horas e horas se divertindo em ver aquilo que produzia funcionar só o deixava '
                                 'mais feliz com seu trabalho, e assim se tornou alguém empenhado em todos os projetos no qual eram oferecidos '
                                 'a ele, já que aquilo era divertido para João! Caso queira verificar o portfólio de sites produzidos pelo '
                                 'mesmo, basta clicar na mensagem com o link abaixo!')

@bot.message_handler(commands=['CSS'])
def python(mensagem_padrao):
    bot.reply_to(mensagem_padrao, 'A paixão pelo design vem desde o trabalho com design gráfico. João tem grande criatividade, e um esforço incrível'
                                  ' em seus trabalhos, que envolvendo o design, no qual o CSS é especialista o deixa muito empolgado, já que seu último trabalho '
                                  'em design gráfico surgiu apenas como um hobby e um passatempo, e acabou virando um trabalho que ele fazia se divertindo.')

@bot.message_handler(commands=['Formacao'])
def python(mensagem_padrao):
    bot.reply_to(mensagem_padrao, 'Bacharel em Ciências da computação, com 4 anos dedicados ao aprendizado do mundo da programação, João se'
                                  'formou com notas acima da média durante os 8 períodos da sua faculdade. Além da faculdade, se somam mais de 300'
                                  ' horas de aprendizado em cursos de programação, em conjunto com ampla experiência no mercado de trabalho, com desenvolvimento'
                                  'de programas focados na análise de dados, armazenamento de dados, processamento de dados, operações matemáticas, '
                                  'interação máquina usuário, etc...')

@bot.message_handler(commands=['Experiencia'])
def python(mensagem_padrao):
    bot.reply_to(mensagem_padrao,'')

def verificar(mensagem_padrao):
    return True

@bot.message_handler(func=verificar)
def responder(mensagem_padrao):
    bot.reply_to(mensagem_padrao, 'Olá! Você está ultilizando o meu bot criado unicamente para o meu portfólio! Caso esteja vendo isso, '
                                  'você deve estar interessado no meu trabalho.. Sobre o que deseja se informar acerca de '
                                  'dev_JoãoA?'
                                  '\n /Python'
                                  '\n /HTML'
                                  '\n /CSS'
                                  '\n /JavaScript'
                                  '\n /Formacao'
                                  '\n /Experiencia')

bot.polling()
