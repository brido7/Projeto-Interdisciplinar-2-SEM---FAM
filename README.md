# Projeto-Interdisciplinar-2-SEM-FAM
Projeto Onça Pitanga

import java.util.Scanner;
public class PI_final1 {
public static void main(String[] args) {
String name, tamanho, cc, cd;
int clie_adm,senha;
int opc, escolha, número, quantidade;
int pgto, n_casa, confirmar1;
int estoque1_P, estoque1_M, estoque1_G;
int estoque2_P, estoque2_M, estoque2_G;
int estoque3_P, estoque3_M, estoque3_G;
int estoque4_P, estoque4_M, estoque4_G;
int estoque5_P, estoque5_M, estoque5_G;
int estoque6_P, estoque6_M, estoque6_G;
int config_estoque, adc_produto, num_peças;
int novo_estoque, adc_tamanho;
double CPF, CEP,num_cardD, num_cartc ;
double preço_biquini, preço_final, frete;
estoque1_P=1;
estoque1_M=2;
estoque1_G=1;
estoque2_P=0;
estoque2_M=0;
estoque2_G=1;
estoque3_P=0;
estoque3_M=1;
estoque3_G=0;
estoque4_P=0;
estoque4_M=1;
estoque4_G=0;
estoque5_P=1;
estoque5_M=2;
estoque5_G=0;
estoque6_P=0;
estoque6_M=2;
estoque6_G=1;
frete=15.00;
preço_biquini=90.00;
Scanner entrada = new Scanner (System.in);
System.out.print ("Bem-Vindo(a), nos diga seu nome: ");
name = entrada.nextLine ();
do {
System.out.println (name + ", você é:");
System.out.println("1.Administrador.");
System.out.println("2.Cliente.");
clie_adm = entrada.nextInt ();
}while ((clie_adm <1) || (clie_adm >2));
if(clie_adm==1) {
do {
System.out.print("Olá, administrador.");
System.out.print(" Digite sua senha:");
senha= entrada.nextInt();
if (senha== 8760) {
System.out.println("Seus acessos
são:");
System.out.println("1. Estoque.");
System.out.println ("2. Adcionar ao
estoque:");
config_estoque=entrada.nextInt();
if (config_estoque==1){
System.out.println();
System.out.println ("Tie Dye");
System.out.println (" tamanho P: " +
estoque1_P);
System.out.println (" tamanho M:" +
estoque1_M);
System.out.println (" tamanho G:" +
estoque1_G);
System.out.println ();
System.out.println ("Cordinha");
System.out.println (" tamanho P: " +
estoque2_P);
System.out.println (" tamanho M: " +
estoque2_M);
System.out.println (" tamanho G: " +
estoque2_G);
System.out.println ();
System.out.println ("Neon Vibes");
System.out.println (" tamanho P: " +
estoque3_P);
System.out.println (" tamanho M: " +
estoque3_M);
System.out.println (" tamanho G: " +
estoque3_G);
System.out.println ();
System.out.println ("Sensação");
System.out.println (" tamanho P: " +
estoque4_P);
System.out.println (" tamanho M: " +
estoque4_M);
System.out.println (" tamanho G: " +
estoque4_G);
System.out.println ();
System.out.println ("Mulicor");
System.out.println (" tamanho P: " +
estoque5_P);
System.out.println (" tamanho M: " +
estoque5_M);
System.out.println (" tamanho G: " +
estoque5_G);
System.out.println ();
System.out.println ("Arco iris");
System.out.println (" tamanho P: " +
estoque6_P);
System.out.println (" tamanho M: " +
estoque6_M);
System.out.println (" tamanho G: " +
estoque6_G);
}
if (config_estoque==2){
System.out.println("Qual produto deseja
adicionar?");
System.out.println("");
System.out.println("1. Tie Dye.");
System.out.println("2. Cordinha.");
System.out.println("3. Neon Vibes.");
System.out.println("4. Sensação.");
System.out.println("5. Multi-Color.");
System.out.println("6. Arco-Íris.");
adc_produto=entrada.nextInt();
if (adc_produto==1) {
System.out.println("Tie Dye.");
System.out.println("Informe o tamanho que
deseja adicionar produtos.");
System.out.println("1. P.");
System.out.println("2. M.");
System.out.println("3. G.");
adc_tamanho=entrada.nextInt();
if (adc_tamanho==1) {
System.out.println("Tamanho P.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque1_P +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho P.");
}
if (adc_tamanho==2) {
System.out.println("Tamanho M.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque1_M +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho M.");
}
if (adc_tamanho==3) {
System.out.println("Tamanho G.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque1_G +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho G.");
}
}
if (adc_produto==2) {
System.out.println("Cordinha.");
System.out.println("Informe o tamanho que
deseja adicionar produtos.");
System.out.println("1. P.");
System.out.println("2. M.");
System.out.println("3. G.");
adc_tamanho=entrada.nextInt();
if (adc_tamanho==1) {
System.out.println("Tamanho P.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque2_P +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho P.");
}
if (adc_tamanho==2) {
System.out.println("Tamanho M.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque2_M +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho M.");
}
if (adc_tamanho==3) {
System.out.println("Tamanho G.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque2_G +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho G.");
}
}
if (adc_produto==3) {
System.out.println("Neon Vibes.");
System.out.println("Informe o tamanho que
deseja adicionar produtos.");
System.out.println("1. P.");
System.out.println("2. M.");
System.out.println("3. G.");
adc_tamanho=entrada.nextInt();
if (adc_tamanho==1) {
System.out.println("Tamanho P.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque3_P +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho P.");
}
if (adc_tamanho==2) {
System.out.println("Tamanho M.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque3_M +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho M.");
}
if (adc_tamanho==3) {
System.out.println("Tamanho G.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque3_G +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho G.");
}
}
if (adc_produto==4) {
System.out.println("Sensação.");
System.out.println("Informe o tamanho que
deseja adicionar produtos.");
System.out.println("1. P.");
System.out.println("2. M.");
System.out.println("3. G.");
adc_tamanho=entrada.nextInt();
if (adc_tamanho==1) {
System.out.println("Tamanho P.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque4_P +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho P.");
}
if (adc_tamanho==2) {
System.out.println("Tamanho M.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque4_M +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho M.");
}
if (adc_tamanho==3) {
System.out.println("Tamanho G.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque4_G +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho G.");
}
}
if (adc_produto==5) {
System.out.println("Multi-Color.");
System.out.println("Informe o tamanho que
deseja adicionar produtos.");
System.out.println("1. P.");
System.out.println("2. M.");
System.out.println("3. G.");
adc_tamanho=entrada.nextInt();
if (adc_tamanho==1) {
System.out.println("Tamanho P.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque5_P +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho P.");
}
if (adc_tamanho==2) {
System.out.println("Tamanho M.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque5_M +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho M.");
}
if (adc_tamanho==3) {
System.out.println("Tamanho G.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque5_G +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho G.");
}
}
if (adc_produto==6) {
System.out.println("Arco-Íris");
System.out.println("Informe o tamanho que
deseja adicionar produtos.");
System.out.println("1. P.");
System.out.println("2. M.");
System.out.println("3. G.");
adc_tamanho=entrada.nextInt();
if (adc_tamanho==1) {
System.out.println("Tamanho P.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque6_P +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho P.");
}
if (adc_tamanho==2) {
System.out.println("Tamanho M.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque6_M +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho M.");
}
if (adc_tamanho==3) {
System.out.println("Tamanho G.");
System.out.println("Quantas peças
deseja adicionar?");
num_peças=entrada.nextInt();
novo_estoque = estoque6_G +
num_peças;
System.out.println("Estoque alterado
com sucesso! O novo número é de " +novo_estoque+ " peças tamanho G.");
}
}
}
}
else {
System.out.println("Senha Inválido,
informe a senha válida.");
}
}while ((senha<8760) || (senha>8760));
}
if (clie_adm==2) {
do {
System.out.print(" " + name +", O que você procura?!");
System.out.print ("temos os seguintes modelos de
biquinis:");
System.out.println ();
System.out.println ("1.Tie dye");
System.out.println ("2.Cortininha");
System.out.println ("3.Neon Vibes");
System.out.println ("4.Sensação");
System.out.println ("5.Multicor");
System.out.println ("6.Arco iris");
System.out.println ();
System.out.print (" Informe a opção desejada:");
escolha = entrada.nextInt ();
System.out.println ();
if((escolha>=1) || (escolha<=6)) {
}
else {
System.out.println ("Código invalido, informe um
código válido:");
}
}while ((escolha<1)|| (escolha>6));
if (escolha==1) {
System.out.println("Você selecionou o modelo Tie Dye.");
do {
if ((estoque1_P>=1) || (estoque1_M>=1) ||
(estoque1_G>=1)) {
System.out.println("Tamanhos disponíveis: ");
if (estoque1_P>=1) {
System.out.println("1. P");
}
if (estoque1_M>=1) {
System.out.println("2. M");
}
if (estoque1_G>=1) {
System.out.println("3. G");
}
System.out.print("Digite o tamanho desejado: ");
opc=entrada.nextInt();
if ((opc >=1) && (opc <=3)){
}
else {
System.out.println("Código Inválido,
informe um código válido.");
}
}
else {
do{
System.out.println ();
System.out.println ("Infelizmente, não
temos nenhum tamanho para o modelo solicitado.");
System.out.println ();
System.out.println ("Digite o numero 0
para encerrar o programa!");
opc=entrada.nextInt ();
}while ((opc<0) || (opc>0));
}
if ((opc==0)) {
do {
System.out.println ("* PROGRAMA
ENCERRADO *");
opc=entrada.nextInt ();
}while ((opc<0) || (opc>0));
}
if ((opc ==1)) {
tamanho = "P.";
System.out.println ();
System.out.println("Você selecionou o
tamanho " + tamanho+".");
System.out.println();
if (estoque1_P>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em
estoque: " + estoque1_P+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque1_P && quantidade<=estoque1_P)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida");
}
}while ((quantidade<estoque1_P) ||
(quantidade>estoque1_P) || (quantidade<=0));
}
}
if (opc ==2) {
tamanho = "M.";
System.out.println(" Você selecionou o
tamanho " +tamanho+".");
if (estoque1_M>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em
estoque: " + estoque1_M+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque1_M && quantidade<=estoque1_M)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida");
}
}while ((quantidade<estoque1_M) ||
(quantidade>estoque1_M) || (quantidade<=0));
}
}
if (opc ==3) {
tamanho = "G.";
System.out.println("Você selecionou o
tamanho " +tamanho+".");
if (estoque1_G>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em
estoque: " + estoque1_G+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque1_G && quantidade<=estoque1_G)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida");
}
}while ((quantidade<estoque1_G) ||
(quantidade>estoque1_G) || (quantidade<=0));
}
}
}while ((opc<1) || (opc >3));
System.out.println ("Deseja continuar:");
System.out.println ("1. Sim");
System.out.println ("2. Não");
confirmar1= entrada.nextInt();
if (confirmar1==1) {
System.out.println ();
System.out.println("Como deseja prosseguir?");
do {
System.out.println("");
System.out.println("1. Finalizar
compra.");
escolha=entrada.nextInt();
if ((escolha >=1) && (escolha <=1)) {
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
if (escolha ==1) {
System.out.println("Você
selecionou " + escolha+".");
System.out.println("Informe seus
dados para prosseguirmos com a compra: ");
System.out.println("");
System.out.print("Digite o seu
CPF ");
CPF=entrada.nextDouble();
System.out.print("Digite o seu
CEP ");
CEP= entrada.nextDouble();
System.out.print("Digite o
numero da sua casa ");
n_casa=entrada.nextInt();
}
}while ((escolha <1)||(escolha >1));
System.out.println ();
System.out.println("Escolha a opção de
pagamento desejada.");
do {
System.out.println("1. Cartão de
Crédito.");
System.out.println("2. Cartão de
Débito.");
pgto=entrada.nextInt();
if ((pgto >=1) && (pgto <=2)) {
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
if (pgto==1) {
cc="Cartão de Crédito.";
System.out.println("Você
selecionou pagamento com " +cc+".");
System.out.print("Digite o
número do cartão: ");
num_cartc=entrada.nextDouble();
System.out.println("Compra
Realizada com sucesso!");
}
if (pgto==2) {
cd="Cartão de Dédito.";
System.out.println("Você
selecionou pagamento com " +cd+".");
System.out.print("Digite o
número do cartão: ");
num_cardD=entrada.nextDouble();
System.out.println("Compra
realizada com sucesso!");
}
}while ((pgto <1) || (pgto >2));
System.out.println("AGRADEÇEMOS SUA
COMPRA, LOGO SEU PRODUTO CHEGARÁ EM SUA CASA!");
}
if (confirmar1==2) {
System.out.println(name+ ", agradecemos sua
procura e preferência");
}
}
if (escolha==2) {
System.out.println ("Você selecionou o modelo
Cordinha.");
do {
if ((estoque2_P>=1) || (estoque2_M>=1) ||
(estoque2_G>=1)) {
System.out.println("Tamanhos disponíveis: ");
if (estoque2_P>=1) {
System.out.println("1. P");
}
if (estoque2_M>=1) {
System.out.println("2. M");
}
if (estoque2_G>=1) {
System.out.println("3. G");
}
System.out.print("Digite o tamanho desejado: ");
opc=entrada.nextInt();
if ((opc >=1) && (opc <=3)){
}
else {
System.out.println("Código Inválido,
informe um código válido.");
}
}
else {
do{
System.out.println ();
System.out.println ("Infelizmente, não
temos nenhum tamanho para o modelo solicitado.");
System.out.println ();
System.out.println ("Digite o numero 0
para encerrar o programa!");
opc=entrada.nextInt ();
}while ((opc<0) || (opc>0));
}
if ((opc==0)) {
do {
System.out.println ("* PROGRAMA
ENCERRADO *");
opc=entrada.nextInt ();
}while ((opc<0) || (opc>0));
}
if (opc ==1){
tamanho = "P.";
System.out.println("Você selecionou o
tamanho " +tamanho+".");
if (estoque2_P>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em estoque:
" + estoque2_P+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque2_P && quantidade<=estoque2_P)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida");
}
}while ((quantidade<estoque2_P) ||
(quantidade>estoque2_P) || (quantidade<=0));
}
}
if (opc ==2) {
tamanho = "M.";
System.out.println("Você selecionou o
tamanho " +tamanho+".");
if (estoque2_M>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em
estoque: " + estoque2_M+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque2_M && quantidade<=estoque2_M)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida");
}
}while ((quantidade<estoque2_M) ||
(quantidade>estoque2_M) || (quantidade<=0));
}
}
if (opc ==3) {
tamanho = "G.";
System.out.println("Você selecionou o
tamanho " +tamanho+".");
if (estoque2_G>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em estoque:
" + estoque2_G+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque2_G && quantidade<=estoque2_G)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida");
}
}while ((quantidade<estoque2_G) ||
(quantidade>estoque2_G) || (quantidade<=0));
}
}
}while ((opc<1) || (opc >3));
System.out.println ("Deseja continuar:");
System.out.println ("1. Sim");
System.out.println ("2. Não");
confirmar1= entrada.nextInt();
if (confirmar1==1) {
System.out.println ();
System.out.println("Como deseja prosseguir?");
do {
System.out.println("");
System.out.println("1. Finalizar
compra.");
escolha=entrada.nextInt();
if ((escolha >=1) && (escolha <=1)) {
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
if (escolha ==1) {
System.out.println("Você
selecionou " + escolha);
System.out.println("Informe seus
dados para prosseguirmos com a compra: ");
System.out.println("");
System.out.print("Digite o seu
CPF ");
CPF=entrada.nextDouble();
System.out.print("Digite o seu
CEP ");
CEP= entrada.nextDouble();
System.out.print("Digite o
numero da sua casa ");
n_casa=entrada.nextInt();
}
}while ((escolha <1)||(escolha >1));
System.out.println ();
System.out.println("Escolha a opção de
pagamento desejada.");
do {
System.out.println("1. Cartão de
Crédito.");
System.out.println("2. Cartão de
Débito.");
pgto=entrada.nextInt();
if ((pgto >=1) && (pgto <=2)) {
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
if (pgto==1) {
cc="Cartão de Crédito.";
System.out.println("Você
selecionou pagamento com " +cc+".");
System.out.print("Digite o
número do cartão: ");
num_cartc=entrada.nextDouble();
System.out.println("Compra
Realizada com sucesso!");
}
if (pgto==2) {
cd="Cartão de Dédito.";
System.out.println("Você
selecionou pagamento com " +cd+".");
System.out.print("Digite o
número do cartão: ");
num_cardD=entrada.nextDouble();
System.out.println("Compra
realizada com sucesso!");
}
}while ((pgto <1) || (pgto >2));
System.out.println("AGRADEÇEMOS SUA
COMPRA, LOGO SEU PRODUTO CHEGARÁ EM SUA CASA!");
}
if (confirmar1==2) {
System.out.println(name+ ", agradecemos sua
procura e preferência");
}
}
if (escolha==3) {
System.out.println ("Você selecionou o modelo
Neon Vibes.");
do {
if ((estoque3_P>=1) || (estoque3_M>=1) ||
(estoque3_G>=1)) {
System.out.println("Tamanhos disponíveis: ");
if (estoque3_P>=1) {
System.out.println("1. P");
}
if (estoque3_M>=1) {
System.out.println("2. M");
}
if (estoque3_G>=1) {
System.out.println("3. G");
}
System.out.print("Digite o tamanho desejado: ");
opc=entrada.nextInt();
if ((opc >=1) && (opc <=3)){
}
else {
System.out.println("Código Inválido,
informe um código válido.");
}
}
else {
do{
System.out.println ();
System.out.println ("Infelizmente, não
temos nenhum tamanho para o modelo solicitado.");
System.out.println ();
System.out.println ("Digite o numero 0
para encerrar o programa!");
opc=entrada.nextInt ();
}while ((opc<0) || (opc>0));
}
if ((opc==0)) {
do {
System.out.println ("* PROGRAMA
ENCERRADO *");
opc=entrada.nextInt ();
}while ((opc<0) || (opc>0));
}
if (opc ==1) {
tamanho = "P.";
System.out.println("Você selecionou o
tamanho " +tamanho+".");
if (estoque3_P>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em estoque:
" + estoque3_P+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque3_P && quantidade<=estoque3_P)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida");
}
}while ((quantidade<estoque3_P) ||
(quantidade>estoque3_P) || (quantidade<=0));
}
}
if (opc ==2) {
tamanho = "M.";
System.out.println("Você selecionou o
tamanho " +tamanho+".");
if (estoque3_M>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em estoque:
" + estoque3_M+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque3_M && quantidade<=estoque3_M)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida");
}
}while ((quantidade<estoque3_M) ||
(quantidade>estoque3_M) || (quantidade<=0));
}
}
if (opc ==3) {
tamanho = "G.";
System.out.println("Você selecionou o
tamanho " +tamanho+".");
if (estoque3_G>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em estoque:
" + estoque3_G+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque3_G && quantidade<=estoque3_G)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida.");
}
}while ((quantidade<estoque3_G) ||
(quantidade>estoque3_G) || (quantidade<=0));
}
}
}while ((opc<1) || (opc >3));
System.out.println ("Deseja continuar:");
System.out.println ("1. Sim");
System.out.println ("2. Não");
confirmar1= entrada.nextInt();
if (confirmar1==1) {
System.out.println ();
System.out.println("Como deseja prosseguir?");
do {
System.out.println("");
System.out.println("1. Finalizar
compra.");
escolha=entrada.nextInt();
if ((escolha >=1) && (escolha <=1)) {
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
if (escolha ==1) {
System.out.println("Você
selecionou " + escolha);
System.out.println("Informe seus
dados para prosseguirmos com a compra: ");
System.out.println("");
System.out.print("Digite o seu
CPF ");
CPF=entrada.nextDouble();
System.out.print("Digite o seu
CEP ");
CEP= entrada.nextDouble();
System.out.print("Digite o
numero da sua casa ");
n_casa=entrada.nextInt();
}
}while ((escolha <1)||(escolha >1));
System.out.println ();
System.out.println("Escolha a opção de
pagamento desejada.");
do {
System.out.println("1. Cartão de
Crédito.");
System.out.println("2. Cartão de
Débito.");
pgto=entrada.nextInt();
if ((pgto >=1) && (pgto <=2)) {
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
if (pgto==1) {
cc="Cartão de Crédito.";
System.out.println("Você
selecionou pagamento com " +cc+".");
System.out.print("Digite o
número do cartão: ");
num_cartc=entrada.nextDouble();
System.out.println("Compra
Realizada com sucesso!");
}
if (pgto==2) {
cd="Cartão de Dédito.";
System.out.println("Você
selecionou pagamento com " +cd+".");
System.out.print("Digite o
número do cartão: ");
num_cardD=entrada.nextDouble();
System.out.println("Compra
realizada com sucesso!");
}
}while ((pgto <1) || (pgto >2));
System.out.println("AGRADEÇEMOS SUA
COMPRA, LOGO SEU PRODUTO CHEGARÁ EM SUA CASA!");
}
if (confirmar1==2) {
System.out.println(name+ ", agradecemos sua
procura e preferência");
}
}
if (escolha==4) {
System.out.println ("Você selecionou o modelo
Sensação.");
do {
if ((estoque4_P>=1) || (estoque4_M>=1)
|| (estoque4_G>=1)) {
System.out.println("Tamanhos
disponíveis: ");
if (estoque4_P>=1) {
System.out.println("1. P");
}
if (estoque4_M>=1) {
System.out.println("2. M");
}
if (estoque4_G>=1) {
System.out.println("3. G");
}
System.out.print("Digite o tamanho
desejado: ");
opc=entrada.nextInt();
if ((opc >=1) && (opc <=3)){
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
}
else {
do{
System.out.println ();
System.out.println ("Infelizmente,
não temos nenhum tamanho para o modelo solicitado.");
System.out.println ();
System.out.println ("Digite o
numero 0 para encerrar o programa!");
opc=entrada.nextInt ();
}while ((opc<0) || (opc>0));
}
if ((opc==0)) {
do {
System.out.println ("*
PROGRAMA ENCERRADO *");
opc=entrada.nextInt ();
}while ((opc<0) || (opc>0));
}
if (opc ==1) {
tamanho = "P.";
System.out.println("Você selecionou o
tamanho " +tamanho+".");
if (estoque4_P>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em
estoque: " + estoque4_P);
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque4_P && quantidade<=estoque4_P)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida.");
}
}while ((quantidade<estoque4_P) ||
(quantidade>estoque4_P) || (quantidade<=0));
}
}
if (opc ==2) {
tamanho = "M.";
System.out.println("Você
selecionou o tamanho " +tamanho+".");
if (estoque4_M>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em
estoque: " + estoque4_M+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque4_M && quantidade<=estoque4_M)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida.");
}
}while ((quantidade<estoque4_M) ||
(quantidade>estoque4_M) || (quantidade<=0));
}
}
if (opc ==3) {
tamanho = "G.";
System.out.println("Você
selecionou o tamanho " +tamanho);
if (estoque4_G>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em
estoque: " + estoque4_G+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque4_G && quantidade<=estoque4_G)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida");
}
}while ((quantidade<estoque4_G) ||
(quantidade>estoque4_G) || (quantidade<=0));
}
}
}while ((opc<1) || (opc >3));
System.out.println ("Deseja continuar:");
System.out.println ("1. Sim");
System.out.println ("2. Não");
confirmar1= entrada.nextInt();
if (confirmar1==1) {
System.out.println ();
System.out.println("Como deseja prosseguir?");
do {
System.out.println("");
System.out.println("1. Finalizar
compra.");
escolha=entrada.nextInt();
if ((escolha >=1) && (escolha <=1)) {
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
if (escolha ==1) {
System.out.println("Você
selecionou " + escolha+".");
System.out.println("Informe seus
dados para prosseguirmos com a compra: ");
System.out.println("");
System.out.print("Digite o seu
CPF ");
CPF=entrada.nextDouble();
System.out.print("Digite o seu
CEP ");
CEP= entrada.nextDouble();
System.out.print("Digite o
numero da sua casa ");
n_casa=entrada.nextInt();
}
}while ((escolha <1)||(escolha >1));
System.out.println ();
System.out.println("Escolha a opção de
pagamento desejada.");
do {
System.out.println("1. Cartão de
Crédito.");
System.out.println("2. Cartão de
Débito.");
pgto=entrada.nextInt();
if ((pgto >=1) && (pgto <=2)) {
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
if (pgto==1) {
cc="Cartão de Crédito.";
System.out.println("Você
selecionou pagamento com " +cc+".");
System.out.print("Digite o
número do cartão: ");
num_cartc=entrada.nextDouble();
System.out.println("Compra
Realizada com sucesso!");
}
if (pgto==2) {
cd="Cartão de Dédito.";
System.out.println("Você
selecionou pagamento com " +cd+".");
System.out.print("Digite o
número do cartão: ");
num_cardD=entrada.nextDouble();
System.out.println("Compra
realizada com sucesso!");
}
}while ((pgto <1) || (pgto >2));
System.out.println("AGRADEÇEMOS SUA
COMPRA, LOGO SEU PRODUTO CHEGARÁ EM SUA CASA!");
}
if (confirmar1==2) {
System.out.println(name+ ", agradecemos sua
procura e preferência.");
}
}
if (escolha==5) {
System.out.println ("Você selecionou o modelo
Multicor.");
do {
if ((estoque5_P>=1) || (estoque5_M>=1)
|| (estoque5_G>=1)) {
System.out.println("Tamanhos
disponíveis: ");
if (estoque5_P>=1) {
System.out.println("1. P");
}
if (estoque5_M>=1) {
System.out.println("2. M");
}
if (estoque5_G>=1) {
System.out.println("3. G");
}
System.out.print("Digite o tamanho
desejado: ");
opc=entrada.nextInt();
if ((opc >=1) && (opc <=3)){
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
}
else {
do{
System.out.println ();
System.out.println ("Infelizmente,
não temos nenhum tamanho para o modelo solicitado.");
System.out.println ();
System.out.println ("Digite o
numero 0 para encerrar o programa!");
opc=entrada.nextInt ();
}while ((opc<0) || (opc>0));
}
if ((opc==0)) {
do {
System.out.println ("*
PROGRAMA ENCERRADO *");
opc=entrada.nextInt ();
}while ((opc<0) || (opc>0));
}
if (opc ==1) {
tamanho = "P.";
System.out.println("Você selecionou o
tamanho " +tamanho+".");
if (estoque4_P>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em
estoque: " +estoque4_P+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque4_P && quantidade<=estoque4_P)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida.");
}
}while ((quantidade<estoque4_P) ||
(quantidade>estoque4_P) || (quantidade<=0));
}
}
if (opc ==2) {
tamanho = "M.";
System.out.println("Você
selecionou o tamanho " +tamanho+".");
if (estoque4_M>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em
estoque: " +estoque4_M+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque4_M && quantidade<=estoque4_M)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida.");
}
}while ((quantidade<estoque4_M) ||
(quantidade>estoque4_M) || (quantidade<=0));
}
}
if (opc ==3) {
tamanho = "G.";
System.out.println("Você
selecionou o tamanho " +tamanho+".");
if (estoque4_G>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em
estoque: " +estoque4_G+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque4_G && quantidade<=estoque4_G)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida.");
}
}while ((quantidade<estoque4_G) ||
(quantidade>estoque4_G) || (quantidade<=0));
}
}
}while ((opc<1) || (opc >3));
System.out.println ("Deseja continuar:");
System.out.println ("1. Sim");
System.out.println ("2. Não");
confirmar1= entrada.nextInt();
if (confirmar1==1) {
System.out.println ();
System.out.println("Como deseja prosseguir?");
do {
System.out.println("");
System.out.println("1. Finalizar
compra.");
escolha=entrada.nextInt();
if ((escolha >=1) && (escolha <=1)) {
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
if (escolha ==1) {
System.out.println("Você
selecionou " + escolha);
System.out.println("Informe seus
dados para prosseguirmos com a compra: ");
System.out.println("");
System.out.print("Digite o seu
CPF ");
CPF=entrada.nextDouble();
System.out.print("Digite o seu
CEP ");
CEP= entrada.nextDouble();
System.out.print("Digite o
numero da sua casa ");
n_casa=entrada.nextInt();
}
}while ((escolha <1)||(escolha >1));
System.out.println ();
System.out.println("Escolha a opção de
pagamento desejada.");
do {
System.out.println("1. Cartão de
Crédito.");
System.out.println("2. Cartão de
Débito.");
pgto=entrada.nextInt();
if ((pgto >=1) && (pgto <=2)) {
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
if (pgto==1) {
cc="Cartão de Crédito.";
System.out.println("Você
selecionou pagamento com " +cc+".");
System.out.print("Digite o
número do cartão: ");
num_cartc=entrada.nextDouble();
System.out.println("Compra
Realizada com sucesso!");
}
if (pgto==2) {
cd="Cartão de Dédito.";
System.out.println("Você
selecionou pagamento com " +cd+".");
System.out.print("Digite o
número do cartão: ");
num_cardD=entrada.nextDouble();
System.out.println("Compra
realizada com sucesso!");
}
}while ((pgto <1) || (pgto >2));
System.out.println("AGRADEÇEMOS SUA
COMPRA, LOGO SEU PRODUTO CHEGARÁ EM SUA CASA!");
}
if (confirmar1==2) {
System.out.println(name+ ", agradecemos sua
procura e preferência.");
}
}
if (escolha==6) {
System.out.println ("Você selecionou o modelo
Arco Iris.");
do {
if ((estoque6_P>=1) || (estoque6_M>=1)
|| (estoque6_G>=1)) {
System.out.println("Tamanhos
disponíveis: ");
if (estoque6_P>=1) {
System.out.println("1. P");
}
if (estoque6_M>=1) {
System.out.println("2. M");
}
if (estoque6_G>=1) {
System.out.println("3. G");
}
System.out.print("Digite o tamanho
desejado: ");
opc=entrada.nextInt();
if ((opc >=1) && (opc <=3)){
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
}
else {
do{
System.out.println ();
System.out.println ("Infelizmente,
não temos nenhum tamanho para o modelo solicitado.");
System.out.println ();
System.out.println ("Digite o
numero 0 para encerrar o programa!");
opc=entrada.nextInt ();
}while ((opc<0) || (opc>0));
}
if ((opc==0)) {
do {
System.out.println ("*
PROGRAMA ENCERRADO *");
opc=entrada.nextInt ();
}while ((opc<0) || (opc>0));
}
if (opc ==1) {
tamanho = "P.";
System.out.println("Você selecionou o
tamanho " +tamanho+".");
if (estoque4_P>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em
estoque: " +estoque4_P+".");
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque4_P && quantidade<=estoque4_P)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida.");
}
}while ((quantidade<estoque4_P) ||
(quantidade>estoque4_P) || (quantidade<=0));
}
}
if (opc ==2) {
tamanho = "M.";
System.out.println("Você
selecionou o tamanho " +tamanho);
if (estoque4_M>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em
estoque: " + estoque4_M);
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque4_M && quantidade<=estoque4_M)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida.");
}
}while ((quantidade<estoque4_M) ||
(quantidade>estoque4_M) || (quantidade<=0));
}
}
if (opc ==3) {
tamanho = "G.";
System.out.println("Você
selecionou o tamanho " +tamanho);
if (estoque4_G>=1){
do {
System.out.println ("Quantos você
deseja:");
System.out.println ("Temos em
estoque: " + estoque4_G);
quantidade= entrada.nextInt();
if ((quantidade>=1 &&
quantidade>=estoque4_G && quantidade<=estoque4_G)) {
preço_final=preço_biquini*quantidade+frete;
System.out.println("O VALOR A SER
PAGO É DE " +preço_final+ " REAIS.");
}
else {
System.out.println ("Quantidade
inválida, informe uma quantidade válida.");
}
}while ((quantidade<estoque4_G) ||
(quantidade>estoque4_G) || (quantidade<=0));
}
}
}while ((opc<1) || (opc >3));
System.out.println ("Deseja continuar:");
System.out.println ("1. Sim");
System.out.println ("2. Não");
confirmar1= entrada.nextInt();
if (confirmar1==1) {
System.out.println ();
System.out.println("Como deseja prosseguir?");
do {
System.out.println("");
System.out.println("1. Finalizar
compra.");
escolha=entrada.nextInt();
if ((escolha >=1) && (escolha <=1)) {
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
if (escolha ==1) {
System.out.println("Você
selecionou " + escolha);
System.out.println("Informe seus
dados para prosseguirmos com a compra: ");
System.out.println("");
System.out.print("Digite o seu
CPF: ");
CPF=entrada.nextDouble();
System.out.print("Digite o seu
CEP: ");
CEP= entrada.nextDouble();
System.out.print("Digite o
numero da sua casa: ");
n_casa=entrada.nextInt();
}
}while ((escolha <1)||(escolha >1));
System.out.println ();
System.out.println("Escolha a opção de
pagamento desejada.");
do {
System.out.println("1. Cartão de
Crédito.");
System.out.println("2. Cartão de
Débito.");
pgto=entrada.nextInt();
if ((pgto >=1) && (pgto <=2)) {
}
else {
System.out.println("Código
Inválido, informe um código válido.");
}
if (pgto==1) {
cc="Cartão de Crédito.";
System.out.println("Você
selecionou pagamento com " +cc+ ".");
System.out.print("Digite o
número do cartão: ");
num_cartc=entrada.nextDouble();
System.out.println("Compra
Realizada com sucesso!");
}
if (pgto==2) {
cd="Cartão de Dédito.";
System.out.println("Você
selecionou pagamento com " +cd+".");
System.out.print("Digite o
número do cartão: ");
num_cardD=entrada.nextDouble();
System.out.println("Compra
realizada com sucesso!");
}
}while ((pgto <1) || (pgto >2));
System.out.println("AGRADEÇEMOS SUA
COMPRA, LOGO SEU PRODUTO CHEGARÁ EM SUA CASA!");
}
if (confirmar1==2) {
S
y
s
t
e
m.o
u
t.p
rin
tln
(
n
a
m
e
+
", a
g
r
a
d
e
c
e
m
o
s
s
u
a
p
r
o
c
u
r
a
e
p
r
e
fe
r
ê
n
cia."
); }} }
}
}
