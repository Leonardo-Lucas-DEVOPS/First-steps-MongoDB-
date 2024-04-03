//cria a colection alunos
use alunos;


//insere objetos dentro da colection alunos
db.alunos.insertOne({
    noem:'Will',
    idade:5,
})
//o insertMany adiciona varios e o insert
    db.alunos.insertMany([
        {nome:'Léo', idade:5,},
        {nome:'Guga', idade:5,},
        {nome:'Lúlú', idade:8,},
    ]);


//retorna todos os dados da colection alunos
db.alunos.find();

//Atualiza apenas um dado 
db.alunos.updateOne(
    {nome:'Léo'},{$set:{nome:'Leeo'}} 
);

// Atualiza todos os documentos na coleção alunos, adicionando o atributo 'sexo' com o valor 'm'
db.alunos.updateMany(
    {}, 
    { $set: { sexo: 'm' } }
);

// Atualiza todos os documentos na coleção alunos com idade 5
db.alunos.updateMany(
    {idade:5}, 
    { $set: { idade:6 } }
);

// Exclui um dado
db.alunos.deleteOne(
     {nome:'Léo'},{$set:{nome:'Leeo'}} 
);

// Exclui dados com...
db.alunos.deleteMany(
    {}, 
    { $set: { sexo: 'm' } }
);
