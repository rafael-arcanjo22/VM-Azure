# VM Azure.

 Virtual Machine.

  O conceito de VM é você pegar uma máquina física e transforma-la em Virtual, todo o recurso físico como por exemplo: HD, Placa de Rede, Processador, Memória Ram são fornecidos pela Microsoft Azure, porém podemos gerenciá-las conforme a nossa necessidade.

 Esse tipo de recurso se chama IaaS ( Infraestrutura como Serviço) no Azure, por exemplo podemos subir Servidores, Datacenters como uma VM e configura-las conforme solicitado.

# Como criar uma VM no AZURE:

 Para criar qualquer recurso no Azure, precisamos pelo ter um RG (Resouce Group) é onde vamos agrupa o recurso e suas dependências, no exemplo temos o RG “Aulas” e dentro dele já temos uma Vnet, onde a VM irá conectar:
![image](https://user-images.githubusercontent.com/119356073/220225147-53f413d7-98e3-496c-8e4d-5daa398204c6.png)

**OBS: Toda VM precisa de uma vnet, não da para criar uma VM sem uma VNET.**

1. No Resource Group clicar em “Create”
![image](https://user-images.githubusercontent.com/119356073/220225195-fbeefe50-761d-4d72-a099-56d82d406c88.png)

2. Pesquina por machine e selecionar “Virtual Machine”
![image](https://user-images.githubusercontent.com/119356073/220225236-abdc1ef9-e993-45fa-80c0-d472f8b9c709.png)

3. Precimos preencher algumas informações importantes em algumas abas na hora da criação da VM:
![image](https://user-images.githubusercontent.com/119356073/220225279-370bc76a-5739-4d79-8127-8127ca61850d.png)
     
 Subscription: Escolher em qual Subs será criado a VM:
![image](https://user-images.githubusercontent.com/119356073/220225308-d14e47cb-5734-4c0c-99d6-51275242d3cd.png)

Resource group: Escolher o RG que está dentro da Sub selecinada:
![image](https://user-images.githubusercontent.com/119356073/220225368-512b61e3-0cd0-4e3a-a180-2408996cce27.png)

Virtual Machine Name: Nome da VM:
![image](https://user-images.githubusercontent.com/119356073/220225429-e19e9b77-aa91-4fd6-a969-57562e89ce94.png)

Region: Localização da VM:
![image](https://user-images.githubusercontent.com/119356073/220225468-2b4f22bb-a83a-48cb-b865-02c39fef4620.png)

Availability options: Criar uma réplica física da VM em outra Zona:
![image](https://user-images.githubusercontent.com/119356073/220225506-32f3a9dc-1c69-4afa-8095-212f64fd71cf.png)

Image: Selecionar o S.O da VM, Windows, Linux etc…
![image](https://user-images.githubusercontent.com/119356073/220225582-d5c0ef5a-2d32-4f43-82a8-aca5d17b5518.png)

Size: Configuração da VM (Processador e Memória):
![image](https://user-images.githubusercontent.com/119356073/220225606-9115ea9b-e153-40ef-bf49-da62567e5134.png)

Administrator Account: Usuário e senha do ADM LOCAL da VM:
![image](https://user-images.githubusercontent.com/119356073/220225643-5fd28dbb-eb53-4830-a85e-835b0d751ea9.png)

Inbound Port Rules: Tipos de conexões na VM, SSH, RDP, HTTP, HTTPS…
![image](https://user-images.githubusercontent.com/119356073/220225677-10109226-c959-44cf-8683-43539b84e406.png)

Discos: Escolher o tipo do Disco se vai ser SSD Premium, Stardand ou HDD:
![image](https://user-images.githubusercontent.com/119356073/220225729-23f4ab31-33e6-42e6-b30a-0aeb452131e2.png)

Virtual Network: Selecionar a Vnet-Subnet em que a VM vai está conectada:
![image](https://user-images.githubusercontent.com/119356073/220225777-a32481be-09e6-4bf8-9b59-d59b21274f09.png)

Criar IP publico e habilitar a porta RDP na interface de Rede:
![image](https://user-images.githubusercontent.com/119356073/220225827-af92c132-5801-4a0e-834f-7add47d25c2e.png)

Clicar na aba Review + Create:
![image](https://user-images.githubusercontent.com/119356073/220225865-cce68017-e5f1-45eb-8f6b-9a2c91154640.png)
##
**Link aula prática: https://www.youtube.com/watch?v=KOsXjBED9hU**








