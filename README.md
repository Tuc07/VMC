public static void main(String[] args) {
    String[] autoresLivro1 = {"KAKAKAK", "PAPAPAPA"};
    Livro livro1 = new Livro("15468K","XXXX",autoresLivro1,"0000000",2000);
    String[] autoresLivro2 = {"XAXAXAXAX"};
    Livro livro2 = new Livro("9857X","ZZZZZZ",autoresLivro2,"11111111",2002);

    System.out.println("Livro 01:");		
    System.out.println("Codigo: "+livro1.getCodigo());
    System.out.println("Titulo: "+livro1.getTitulo());
    System.out.println("Autores: "+String.join("e", livro1.getAutores()));
    System.out.println("ISBN: "+livro1.getIsbn());
    System.out.println("Ano: "+livro1.getAno());
    System.out.println("---------------------");

    System.out.println("Livro 02:");
    System.out.println("Codigo: "+livro2.getCodigo());
    System.out.println("Titulo: "+livro2.getTitulo());
    System.out.println("Autores: "+livro2.getAutores());
    System.out.println("ISBN: "+livro2.getIsbn());
    System.out.println("Ano: "+livro2.getAno());

    /////////////////////////////////////////////////////////////
    public class Livro {
    private String codigo;
    private String titulo;
    private String[] autores;
    private String isbn;
    private int ano;

    public Livro(String codigo, String titulo, String[] autores, String isbn, int ano) {
        this.codigo = codigo;
        this.titulo = titulo;
        this.autores = autores;
        this.isbn = isbn;
        this.ano = ano;
    }

    public String getCodigo() {
        return codigo;
    }
    public void setCodigo(String codigo) {
        this.codigo = codigo;
    }
    public String getTitulo() {
        return titulo;
    }
    public void setTitulo(String titulo) {
        this.titulo = titulo;
    }
    public String[] getAutores() {
        return autores;
    }
    public void setAutores(String[] autores) {
        this.autores = autores;
    }
    public String getIsbn() {
        return isbn;
    }
    public void setIsbn(String isbn) {
        this.isbn = isbn;
    }
    public int getAno() {
        return ano;
    }
    public void setAno(int ano) {
        this.ano = ano;
    }
}[Aula2005.zip](https://github.com/user-attachments/files/28060137/Aula2005.zip)
