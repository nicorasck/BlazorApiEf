# Uppgift Blazor / API / EF
_______________________________________________________________
Skapa ett nytt Blazor WASM Standalone projekt (använd .NET 8).

Konfigurera infrastrukturen för Entity Framework Core.

Entitet: User
- Id
- Username
- Email
- List<Blogpost>

Entitet Blogpost
- Id
- Title
- Content
- Created
- AuthorID
- User Author

User har alltså en lista av objekttypen BlogPost. Blogpost har AuthorId och Author som är avtypen User.
