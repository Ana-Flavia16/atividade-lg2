# atividade-lg2
Pilha
package ex.pilha;

import java.util.LinkedList; import java.util.List;

public class Pilha {

private List<String> nomes = new LinkedList<String>();

public void push(String nome) (
	nomes.add(nome);
)

public String pop() {
	return nomes.remove(nomes.size()-1);
}

public String toString() {
	return nomes.toString();
}
}


FILA
package ex.fila;

import java.util.LinkedList; import java.util.List;

public class Fila {

private List<String> alunos = new LinkedList<String>();

public void push(String aluno) (
	aluno.add(aluno);
)

public String pop() {
	return alunos.remove(0);
}

public boolean vaza() {
	return alunos.isEmpty();
}
public String toString() {
	return alunos.toString();
}
}
