
## FULL CODE 

struct ContentView: View {
    var body: some View {
        VStack {
            Image(systemName: "globe")
                .imageScale(.large)
                .foregroundStyle(.tint)
            Text("Hello, CS193!")
        }
        .padding()
    }
}



### struct ContentView: View 

    - struct ContentView: View, onde struct é a palavra-chave que significa que é uma estrutura, ContentView é o nome que foi dado a ela, e View é o como essa estrutura se comporta... no caso a estrutura ContentView se comporta como uma View...


### var body: some View

    - var body: some View {}: var significa que ela é uma variavel, o body somente nomeia esta variavel, e o some View, é o tipo da variavel, como ela se comporta, que é chamado de protocolo... Porem não se deve confundir essa variavel com a variavel comum, por exemplo:
        - caso viesse escrito var i: int ou var s: String, significa que elas são estruturas do tipo int e do tipo string, e não uma string e um int em si...

#### Computed Property ####

    - Essa parte que vem apos o View (que esta entra as {}), é chamado de propriedade porque é uma propriedade dessa estrutura.
    
        VStack {
            Image(systemName: "globe")
                .imageScale(.large)
                .foregroundStyle(.tint)
            Text("Hello, CS193!")
        }
        .padding()
    }


    
    