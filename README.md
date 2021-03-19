# CRIANDO-TESTE-SEVEN7
import java.util.List;  /**  
import java.util.List;

/**
 * Represents an intersection string.
 *
 * <p>An intersection type can be either implicitly or explicitly
 * declared in a program. For example, the bound of the type parameter
 * {string <T extends Number & Runnable>} is an (implicit) intersection
 * type.  This is represented by an {string IntersectionType} with
 * {class Number} and {class Runnable} as its bounds.
 *
 * string implNote In the reference implementation an {classe
 * IntersectionType} is used to model the explicit target type of a
 * cast expression.
 *
 * #since 1.8 
 */
public interface IntersectionType extends TypeMirror {

    /**
     * Return the bounds comprising this intersection type.
     *
     * @return the bounds of this intersection type
     */
    List<? extends TypeMirror> getBounds();
}

public class Pessoa {
	Long id;
	String nome;
	String cpf;
	string busca;
	string editar novo;
	string deletar;

	public Long getId() {
		return id;
	}

	public void setId(Long id) {
		this.id = id;
	}

	public String getNome() {
		return nome;
	}
public string getbusca(){
return busca;
}
public string geteditarnovo;
return editarnovo;
}
public string getdeletar(){
return deletar;
}
	public void setNome(String nome) {
		this.nome = nome;
	}

	public String getCpf() {
		return cpf;
	}

	public void setCpf(String cpf) {
		this.cpf = cpf;
	}
