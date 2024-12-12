
######
# Day 1
######

\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
######
# Day 2
######
Fungsi eksternal ialah agar file html tersebut tidak terlalu panjang dan lebih terstruktur.


# COLOR
gradasi : linear-gradient(blue, yellow)
hsl, rgb | + a artinya a itu trasnparant 

# Ukuran size text
px, pt, cm, mm. in,
%, em, rem, vw. bh

## MATERI GIT
PS C:\Users\User\projects\Projects\bc_phincon_3> `git status`
On branch master
nothing to commit, working tree clean
_Untuk melihat di Branch manakah kita berada. Dan jawabannya ialah berada di Branch Master_

PS C:\Users\User\projects\Projects\bc_phincon_3> `git checkout -b main`
_Untuk pindah ke branch main_

PS C:\Users\User\projects\Projects\bc_phincon_3> `git status`
On branch main
nothing to commit, working tree clean
_Dan kini sudah pindah ke branch main_

PS C:\Users\User\projects\Projects\bc_phincon_3> `git remote -v`

PS C:\Users\User\projects\Projects\bc_phincon_3> `git remote add origin https://github.com/Qarslan/bc_phincon_3.git`

PS C:\Users\User\projects\Projects\bc_phincon_3> `git remote -v`
origin  https://github.com/Qarslan/bc_phincon_3.git (push)

PS C:\Users\User\projects\Projects\bc_phincon_3> `git pull origin main`
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 857 bytes | 1024 bytes/s, done.
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
fatal: refusing to merge unrelated histories

PS C:\Users\User\projects\Projects\bc_phincon_3> `git pull origin main --allow-unrelated-histories`
From https://github.com/Qarslan/bc_phincon_3
 * branch            main       -> FETCH_HEAD
Merge made by the 'ort' strategy.
 README.md | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

PS C:\Users\User\projects\Projects\bc_phincon_3> `git push origin main`
Enumerating objects: 23, done.
Counting objects: 100% (23/23), done.
Delta compression using up to 4 threads
Compressing objects: 100% (18/18), done.
Writing objects: 100% (22/22), 4.10 KiB | 233.00 KiB/s, done.
Total 22 (delta 6), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (6/6), done.
To https://github.com/Qarslan/bc_phincon_3.git
   33c6287..a1f13b7  main -> main

## Pengkaitkan local storage kita ke github
_Dengan cara Pull terlebih dahulu untuk meng-connect-kan github tersebut dengan local kita, lalu kemudian setelah sudah di kaitkan atau sudah di pull baru kita upload atau push ke github repo tersebut_
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\


\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\ START DAY 3 \\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
```MATERI```
1.  CSS Position
\\ Position `Static`


\\ Position `Relative`
_relative itu tidak akan menimpa sesuatu blok apapun_
    .index {
        position: relative;
        left: 20px;
        top: 30px;
    }

\\ Position `fixed`
_Seperti logo WA yang tetap tak berubah di tampilan device, biasanya juga selain fixed itu sticky_
    .position {
        position: fixed;
    }


\\ Position `Absolute`
_Menimpa konten div lainnya yang semisal relative di timpa dengan div absolute_
    .absolute {
        position: absolute;
        top: ;
    }

\\ Position `Sticky`
_Penggunaan untuk tetap selalu mengikuti dan berada di paling atas ketika di scroll ke bawah_
    .position {
        position: sticky;
    }


\\ Flex Box
_Untuk mengurutkan menjadi kesamping yang diawalnya itu  ke bawah sperti biasa_
    {
        display: flex;
    }

\\ Flex Direction


\\ Image
    {
        width: 100%;
    }

#####
# Display
#####

Display;
\\Inline _akan sejajar nantinya_
\\Block
\\flex
\\grid

_flex dan grid hampir sama_

##
Display;
none
hidden
\\\\\\\\\\\\\\
# --------------- #
*Z-INDEX*
`FUNGSI`
sama halnya seperti modal
[Sangat berfungsi banget dengan sisi penempatan.]
==================
_mediascreen_ untuk responsive.
_padding_ untuk menggeser dalamnya
_margin_ untuk menggesar luarnya

# -------------------- #
overflow

# ------------------- #
# Letter Spacing 
# Text Formating

# Text Shadow
# Modular Scales

# Responsive
_Menggunakan @media_

1rem = 16px

\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
# JAVASCRIPT
`Behavior`

Server : `node.js`
Frontend : `React JS`
Mobile : `React Native`

Variable;
- `automatically`
- `var`
- `let`
- `const`
var, let, const = _Declarator_

\\Perbedaannya itu pada saat function tersebut dengan didalam ataupun diluar function tersebut.\\

`Budayakan selalu dengan descriptive name (langsung namanya)`

_huruf besar kecilnya juga pun nanti akan berpengaruh_

\\ String : Berupa text
\\ number : float, double
\\ int (integer)  
\\ BigInt (Big Integer)

`Tidak harus titik koma di javascript itu`

\\ bisa juga memakai $ (dollar) ataupun _ (underscore)

let mempunyai blockscope.
dan blockscopenya local.
`hanya berada didalam function let itu berada.`
`Hanya bisa berada didalam scope itu aja diaksesnya`

\\var bisa diakses di globalscape.
\\ karena seperti itu maka rentan dari securitynya itu yang bisa diakses di globalscope

# tidak memakai var?
_karena var bisa diakses diluar scope maka itu tidak akan aman jika data didalam scope yang memakai var itu data sensitif_

######
# ARRAY
`untuk membuat format data`

# Object itu mempunyai key valuenya ditiap data tersebut



== membandingkan biasa saja
=== membanding nilai dan type datanya juga

"60"<"5"= false

dilihat dari string itu urutan didepannya


Biasanya yang di pakai itu NOT AND OR

_TEruntuk x_
let x;
x = 15
x = "Fulan"
maka yang kepanggil itu ialah fulan yang string tersebut

_``, '', ""_
\\lebih aman menggunakan backtick ``\\


_Empty Values berbeda dengan Undefined_
\\Empty values
`let name = "";`
\\ Undefined
`let name;`
======== 


_Teruntuk function_
\\ Dibuatkan untuk kerangkanya terlebih dahulu


_Arrow Function_
gunakan arrow function


######
`Task`
_name :_ Kalkulator node js
Gunakan bahasa inggris
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
