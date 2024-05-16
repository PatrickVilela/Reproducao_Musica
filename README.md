# Reproducao_Musica
Desenvolvendo um aplicativo que permita aos usuários criar e gerenciar listas de reprodução de música, reproduzindo faixas de áudio e fornecendo recursos de organização e classificação.

# Entidades:
## Usuário:

### Atributos: 
ID, nome de usuário, senha.
### Relacionamentos: 
Pode ter várias listas de reprodução.

## Lista de Reprodução:

### Atributos: 
ID, título, descrição, data de criação.
### Relacionamentos: 
Pertence a um usuário. Pode conter várias músicas.

## Música:

### Atributos: 
ID, título, artista, álbum, duração, arquivo de áudio.
### Relacionamentos: 
Pode pertencer a várias listas de reprodução.

## Relacionamentos:

Um usuário pode ter várias listas de reprodução.
Uma lista de reprodução pertence a um único usuário.
Uma lista de reprodução pode conter várias músicas.
Uma música pode pertencer a várias listas de reprodução.

Com base nesse modelo, você pode implementar um aplicativo que permita aos usuários criar e gerenciar suas próprias listas de reprodução de música, adicionar e remover músicas, reproduzir faixas de áudio e fornecer recursos de organização e classificação, como ordenação por título, artista ou álbum.
