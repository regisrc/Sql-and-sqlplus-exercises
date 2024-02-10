CREATE TABLE Filmes (
    Id NUMBER PRIMARY KEY,
    Nome VARCHAR2(120),
    DataLancamento DATE,
    Valor NUMBER(10,2),
    Genero VARCHAR2(120)
);

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(1, 'O Poderoso Chefão', TO_DATE('1972-03-24', 'YYYY-MM-DD'), 12.99, 'Drama');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(2, 'Pulp Fiction: Tempo de Violência', TO_DATE('1994-10-14', 'YYYY-MM-DD'), 14.99, 'Crime, Drama');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(3, 'O Senhor dos Anéis: O Retorno do Rei', TO_DATE('2003-12-17', 'YYYY-MM-DD'), 17.50, 'Aventura, Fantasia');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(4, 'Forrest Gump: O Contador de Histórias', TO_DATE('1994-07-06', 'YYYY-MM-DD'), 11.25, 'Drama, Romance');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(5, 'Matrix', TO_DATE('1999-04-08', 'YYYY-MM-DD'), 9.99, 'Ação, Ficção Científica');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(6, 'O Silêncio dos Inocentes', TO_DATE('1991-02-14', 'YYYY-MM-DD'), 13.75, 'Crime, Drama, Suspense');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(7, 'Interestelar', TO_DATE('2014-11-07', 'YYYY-MM-DD'), 16.80, 'Aventura, Drama, Ficção Científica');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(8, 'Gladiador', TO_DATE('2000-05-05', 'YYYY-MM-DD'), 12.50, 'Ação, Aventura, Drama');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(9, 'O Resgate do Soldado Ryan', TO_DATE('1998-07-24', 'YYYY-MM-DD'), 14.25, 'Drama, Guerra');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(10, 'Os Bons Companheiros', TO_DATE('1990-09-21', 'YYYY-MM-DD'), 13.99, 'Biografia, Crime, Drama');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(11, 'A Origem', TO_DATE('2010-07-30', 'YYYY-MM-DD'), 15.50, 'Ação, Aventura, Ficção Científica');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(12, 'A Lista de Schindler', TO_DATE('1993-12-15', 'YYYY-MM-DD'), 12.25, 'Biografia, Drama, História');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(13, 'Cidade de Deus', TO_DATE('2002-02-08', 'YYYY-MM-DD'), 11.99, 'Crime, Drama');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(14, 'O Grande Truque', TO_DATE('2006-11-10', 'YYYY-MM-DD'), 14.50, 'Drama, Mistério, Suspense');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(15, 'Scarface', TO_DATE('1983-12-09', 'YYYY-MM-DD'), 13.25, 'Crime, Drama');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(16, 'Laranja Mecânica', TO_DATE('1971-02-02', 'YYYY-MM-DD'), 10.99, 'Crime, Drama, Ficção Científica');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(17, 'Os Suspeitos', TO_DATE('1995-08-16', 'YYYY-MM-DD'), 12.80, 'Crime, Drama, Mistério');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(18, 'O Lobo de Wall Street', TO_DATE('2013-12-25', 'YYYY-MM-DD'), 15.25, 'Biografia, Crime, Drama');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(19, 'O Sexto Sentido', TO_DATE('1999-08-06', 'YYYY-MM-DD'), 11.99, 'Drama, Mistério, Suspense');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(20, 'Os Intocáveis', TO_DATE('1987-06-03', 'YYYY-MM-DD'), 12.50, 'Biografia, Crime, Drama');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(21, 'Coração Valente', TO_DATE('1995-09-22', 'YYYY-MM-DD'), 14.75, 'Biografia, Drama, História');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(22, 'Clube da Luta', TO_DATE('1999-10-29', 'YYYY-MM-DD'), 13.80, 'Drama');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(23, 'De Volta para o Futuro', TO_DATE('1985-07-03', 'YYYY-MM-DD'), 10.50, 'Aventura, Comédia, Ficção Científica');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(24, 'O Auto da Compadecida', TO_DATE('2000-09-10', 'YYYY-MM-DD'), 12.99, 'Comédia');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(25, 'O Iluminado', TO_DATE('1980-06-13', 'YYYY-MM-DD'), 11.25, 'Drama, Terror');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(26, 'A Viagem de Chihiro', TO_DATE('2001-07-20', 'YYYY-MM-DD'), 14.50, 'Animação, Aventura, Família');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(27, 'Vingadores: Ultimato', TO_DATE('2019-04-26', 'YYYY-MM-DD'), 17.25, 'Ação, Aventura, Ficção Científica');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(28, 'Django Livre', TO_DATE('2013-01-18', 'YYYY-MM-DD'), 14.99, 'Drama, Faroeste');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(29, 'O Rei Leão', TO_DATE('1994-07-15', 'YYYY-MM-DD'), 12.50, 'Animação, Aventura, Drama');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(30, 'Batman: O Cavaleiro das Trevas', TO_DATE('2008-07-18', 'YYYY-MM-DD'), 15.99, 'Ação, Crime, Drama');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(31, 'O Labirinto do Fauno', TO_DATE('2006-10-20', 'YYYY-MM-DD'), 13.75, 'Drama, Fantasia, Guerra');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(32, 'Tubarão', TO_DATE('1975-06-20', 'YYYY-MM-DD'), 11.99, 'Aventura, Suspense');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(33, 'Os Caçadores da Arca Perdida', TO_DATE('1981-06-12', 'YYYY-MM-DD'), 12.50, 'Aventura');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(34, 'E o Vento Levou', TO_DATE('1940-12-15', 'YYYY-MM-DD'), 10.99, 'Drama, Romance');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(35, 'O Show de Truman: O Show da Vida', TO_DATE('1998-09-04', 'YYYY-MM-DD'), 11.25, 'Comédia, Drama, Ficção Científica');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(36, 'Whiplash: Em Busca da Perfeição', TO_DATE('2015-02-08', 'YYYY-MM-DD'), 14.50, 'Drama, Música');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(37, 'O Fabuloso Destino de Amélie Poulain', TO_DATE('2001-04-25', 'YYYY-MM-DD'), 13.80, 'Comédia, Romance');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(38, 'O Pianista', TO_DATE('2002-01-24', 'YYYY-MM-DD'), 14.25, 'Biografia, Drama, Guerra');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(39, 'A Lista de Schindler', TO_DATE('1993-12-15', 'YYYY-MM-DD'), 12.25, 'Biografia, Drama, História');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(40, 'O Artista', TO_DATE('2012-02-10', 'YYYY-MM-DD'), 13.99, 'Comédia, Drama, Romance');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(41, 'A Origem', TO_DATE('2010-07-30', 'YYYY-MM-DD'), 15.50, 'Ação, Aventura, Ficção Científica');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(42, 'O Fabuloso Destino de Amélie Poulain', TO_DATE('2001-04-25', 'YYYY-MM-DD'), 13.80, 'Comédia, Romance');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(43, 'Interestelar', TO_DATE('2014-11-07', 'YYYY-MM-DD'), 16.80, 'Aventura, Drama, Ficção Científica');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(44, 'O Pianista', TO_DATE('2002-01-24', 'YYYY-MM-DD'), 14.25, 'Biografia, Drama, Guerra');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(45, 'A Lista de Schindler', TO_DATE('1993-12-15', 'YYYY-MM-DD'), 12.25, 'Biografia, Drama, História');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(46, 'O Artista', TO_DATE('2012-02-10', 'YYYY-MM-DD'), 13.99, 'Comédia, Drama, Romance');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(47, 'A Origem', TO_DATE('2010-07-30', 'YYYY-MM-DD'), 15.50, 'Ação, Aventura, Ficção Científica');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(48, 'O Fabuloso Destino de Amélie Poulain', TO_DATE('2001-04-25', 'YYYY-MM-DD'), 13.80, 'Comédia, Romance');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(49, 'Interestelar', TO_DATE('2014-11-07', 'YYYY-MM-DD'), 16.80, 'Aventura, Drama, Ficção Científica');

INSERT INTO Filmes (Id, Nome, DataLancamento, Valor, Genero) VALUES
(50, 'O Pianista', TO_DATE('2002-01-24', 'YYYY-MM-DD'), 14.25, 'Biografia, Drama, Guerra');

Selecione todos os filmes da tabela "Filmes".
Selecione os filmes lançados após o ano de 2000.
Selecione os filmes lançados entre os anos de 1990 e 2000.
Selecione os filmes que custam mais de $15.
Selecione os filmes do gênero "Ação".
Selecione os filmes do gênero "Drama" ou "Suspense".
Selecione os filmes cujos nomes começam com a letra "O".
Selecione os filmes ordenados por nome em ordem alfabética.
Selecione os 10 primeiros filmes da tabela.
Selecione os filmes agrupados por gênero.
Selecione a contagem total de filmes na tabela.
Selecione a data de lançamento mais antiga na tabela.
Selecione o valor médio dos filmes na tabela.
Selecione os filmes ordenados por data de lançamento em ordem decrescente.
Selecione os filmes lançados no ano de 1999 com um valor superior a $10.
Selecione os filmes cujo nome contenha a palavra "Senhor".
Selecione os filmes cujo gênero contenha a palavra "Drama".
Selecione os filmes lançados no primeiro trimestre do ano.
Selecione os filmes lançados nos últimos 5 anos.
Selecione os filmes cujo nome comece com a letra "A" e termine com a letra "o".
Selecione os filmes cujo valor esteja entre $10 e $20.
Selecione os filmes cuja data de lançamento seja um dia de semana (de segunda a sexta-feira).
Selecione os filmes agrupados por ano de lançamento, mostrando a quantidade de filmes lançados em cada ano.
Selecione os filmes cujo nome tenha pelo menos 10 caracteres.
Selecione os filmes que não tenham um gênero especificado.
