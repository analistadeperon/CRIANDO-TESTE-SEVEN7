# CRIANDO-TESTE-SEVEN7
import java.util.List;  /**  

package funcionario;
 
public class Funcionario {
 
    protected int numeroRegistro;
    protected String nome;
    protected String funcao;
    protected float salario;
    protected String situacao;
 
    public Funcionario() {
    }
 
    public Funcionario(int _numeroRegistro, String _nome, String _funcao, float _salario, String _situacao){
        numeroRegistro = _numeroRegistro;
        nome = _nome;
        funcao = _funcao;
        salario = _salario;
        situacao = _situacao;
    }
 
    public void DefinirNumeroRegistro(int _numeroRegistro){
         numeroRegistro = _numeroRegistro;
    }
 
    public int ObterNumeroRegistro(){
        return(numeroRegistro);
    }
 
    public void DefinirNome(String _nome){
        nome = _nome;
    }
 
    public String ObterNome(){
        return(nome);
    }
 
    public void DefinirFuncao(String _funcao){
        funcao = _funcao;
    }
 
    public String ObterFuncao(){
        return(funcao);
    }
 
    public void DefinirSalario(float _salario){
        salario = _salario;
    }
 
    public float ObterSalario(){
        return(salario);
    }
 
    public void DefinirSituacao(String _situacao){
        situacao = _situacao;
    }
 
    public String ObterSituacao(){
        return(situacao);
    }
}
package funcionario;
 
public class FuncionarioEfetivo extends Funcionario {
 
    private String dataAdmissao;
    private String dataDemissao;
 
    public FuncionarioEfetivo() {
    }
 
    public FuncionarioEfetivo(int _numeroRegistro, String _nome, String _funcao, float _salario, String _situacao, String _dataAdmissao, String _dataDemissao){
        numeroRegistro = _numeroRegistro;
        nome = _nome;
        funcao = _funcao;
        salario = _salario;
        situacao = _situacao;
        dataAdmissao = _dataAdmissao;
        dataAdmissao = _dataAdmissao;
        dataDemissao = _dataDemissao;
    }
 
    public void DefinirDataAdmissao(String _dataAdmissao){
        dataAdmissao = _dataAdmissao;
    }
 
    public String ObterDataAdmissao(){
        return(dataAdmissao);
    }
 
    public void DefinirDataDemissao(String _dataDemissao){
        dataDemissao = _dataDemissao;
    }
 
    public String ObterDataDemissao(){
        return(dataDemissao);
    }
}
package funcionario;
 
public class FuncionarioTemporario extends Funcionario{
 
    private String dataInicio;
    private String duracaoMeses;
 
    public FuncionarioTemporario() {
    }
 
    public FuncionarioTemporario(int _numeroRegistro, String _nome, String _funcao, float _salario, String _situacao, String _dataInicio, String _duracaoMeses){
        numeroRegistro = _numeroRegistro;
        nome = _nome;
        funcao = _funcao;
        salario = _salario;
        situacao = _situacao;
        dataInicio = _dataInicio;
        duracaoMeses = _duracaoMeses;
    }
 
    public void DefinirDataInicio(String _dataInicio){
        dataInicio = _dataInicio;
    }
 
    public String ObterDataInicio(){
        return(dataInicio);
    }
 
    public void DefinirDuracaoMeses(String _duracaoMeses){
        duracaoMeses = _duracaoMeses;
    }
 
    public String ObterDuracaoMeses(){
        return(duracaoMeses);
    }
}
package funcionario;
 
public class FuncionarioTerceiro extends Funcionario{
 
    private String dataInicio;
    private String duracaoContrato;
    private String nomeEmpresa;
 
    public FuncionarioTerceiro() {
    }
 
    public FuncionarioTerceiro(int _numeroRegistro, String _nome,String_botao z entrar e m sair, String _funcao, float _salario, String _situacao, String _dataInicio, String _duracaoContrato, String _nomeEmpresa){
        numeroRegistro = _numeroRegistro;
        nome = _nome;
        funcao = _funcao;
        salario = _salario;
        situacao = _situacao;
        dataInicio = _dataInicio;
        duracaoContrato = _duracaoContrato;
        nomeEmpresa = _nomeEmpresa;
        botaoacesso = botaoacesso;
        { public void definirbotaoacesso(z entar e m sair)}
        botaoacesso=botaoacesso;
    }
 
    public void DefinirDataInicio(String _dataInicio){
        dataInicio = _dataInicio;
    }
 
    public String ObterDataInicio(){
        return(dataInicio);
    }
 
    public void DefinirDuracaoContrato(String _duracaoContrato){
        duracaoContrato = _duracaoContrato;
    }
 
    public String ObterDuracaoContrato(){
        return(duracaoContrato);
    }
 
    public void DefinirNomeEmpresa(String _nomeEmpresa){
        nomeEmpresa = _nomeEmpresa;
    }
 
    public String ObterNomeEmpresa(){
        return(nomeEmpresa);
    }
 
}
