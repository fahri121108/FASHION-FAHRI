isi dev<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>FAHRI FASHION STORE</title>

<style>
body{
    margin:0;
    background:#0f1117;
    color:white;
    font-family:Arial;
}

header{
    background:#171c29;
    padding:20px;
    text-align:center;
}

.container{
    padding:20px;
    max-width:1200px;
    margin:auto;
}

.card{
    background:#1b2130;
    padding:20px;
    border-radius:15px;
    margin-bottom:20px;
}

input,select{
    width:100%;
    padding:12px;
    margin-top:10px;
    border:none;
    border-radius:10px;
    box-sizing:border-box;
}

button{
    width:100%;
    padding:12px;
    margin-top:10px;
    border:none;
    border-radius:10px;
    cursor:pointer;
}

.grid{
    display:grid;
    grid-template-columns:
    repeat(auto-fill,minmax(220px,1fr));
    gap:15px;
}

.item{
    background:#1b2130;
    border-radius:15px;
    padding:15px;
}

.item img{
    width:100%;
    height:260px;
    object-fit:cover;
    border-radius:10px;
}
</style>
</head>
<body>

<header>
<h1>FAHRI FASHION STORE</h1>
<p>Roblox Outfit Catalog</p>
</header>

<div class="container">

<div class="card">

<h2>Login / Register</h2>

<input id="email"
placeholder="Email">

<input id="password"
type="password"
placeholder="Password">

<button onclick="register()">
Daftar
</button>

<button onclick="login()">
Login
</button>

<button onclick="logout()">
Logout
</button>

<p id="status">
Belum Login
</p>

</div>

<div id="adminPanel"
class="card"
style="display:none;">

<h2>Panel Admin</h2>

<input id="nama"
placeholder="Nama Outfit">

<select id="tipe">

<option>Baju</option>
<option>Celana</option>
<option>Setelan</option>

</select>

<input id="harga"
placeholder="Harga Robux">

<input id="gambar"
placeholder="Link Thumbnail">

<input id="link"
placeholder="Link Roblox Item">

<button onclick="tambah()">
Tambah Outfit
</button>

</div>

<h2>Katalog Outfit</h2>

<div id="list"
class="grid"></div>

</div>

<script type="module">

import { initializeApp }
from
"https://www.gstatic.com/firebasejs/10.12.2/firebase-app.js";

import {
 getAuth,
 createUserWithEmailAndPassword,
 signInWithEmailAndPassword,
 signOut
}
from
"https://www.gstatic.com/firebasejs/10.12.2/firebase-auth.js";

import {
 getFirestore,
 collection,
 addDoc,
 getDocs
}
from
"https://www.gstatic.com/firebasejs/10.12.2/firebase-firestore.js";


/* ===========================
ISI CONFIG FIREBASE DISINI
=========================== */

const firebaseConfig = {

 apiKey:
 "ISI_SENDIRI",

 authDomain:
 "ISI_SENDIRI",

 projectId:
 "ISI_SENDIRI",

 storageBucket:
 "ISI_SENDIRI",

 messagingSenderId:
 "ISI_SENDIRI",

 appId:
 "ISI_SENDIRI"

};

/* ======================= */

const app =
initializeApp(firebaseConfig);

const auth =
getAuth(app);

const db =
getFirestore(app);


/* ===========================
ISI EMAIL ADMIN DISINI
=========================== */

const ADMIN_EMAIL =
"ISI_EMAIL_ADMIN";

/* ===========================
ISI DEVICE ADMIN DISINI
contoh:
FAHRI_HP_2026
=========================== */

const ADMIN_DEVICE =
"ISI_DEVICE";


window.register =
async function(){

    try{

        await
        createUserWithEmailAndPassword(
            auth,
            email.value,
            password.value
        );

        alert(
        "Akun berhasil dibuat"
        );

    }catch(e){

        alert(e.message);

    }

}


window.login =
async function(){

    try{

        await
        signInWithEmailAndPassword(
            auth,
            email.value,
            password.value
        );

        status.innerText =
        "Login Berhasil";

        const user =
        auth.currentUser;

        const device =
        localStorage.getItem(
            "admin_device"
        );

        if(
            user.email
            ===
            ADMIN_EMAIL

            &&

            device
            ===
            ADMIN_DEVICE
        ){

            adminPanel.style.display =
            "block";

        }

    }catch(e){

        alert(e.message);

    }

}


window.logout =
async function(){

    await signOut(auth);

    status.innerText =
    "Belum Login";

    adminPanel.style.display =
    "none";

}


window.tambah =
async function(){

    await addDoc(

        collection(
            db,
            "outfits"
        ),

        {

            nama:
            nama.value,

            tipe:
            tipe.value,

            harga:
            harga.value,

            gambar:
            gambar.value,

            link:
            link.value

        }

    );

    loadData();

}


async function loadData(){

    const query =
    await getDocs(

        collection(
            db,
            "outfits"
        )

    );

    let html = "";

    query.forEach(doc=>{

        const o =
        doc.data();

        html += `

        <div class="item">

        <img src="${o.gambar}">

        <h3>${o.nama}</h3>

        <p>${o.tipe}</p>

        <p>${o.harga} Robux</p>

        <a
        href="${o.link}"
        target="_blank">

        <button>
        Beli di Roblox
        </button>

        </a>

        </div>

        `;

    });

    list.innerHTML =
    html;

}

loadData();

</script>

</body>
</html>
