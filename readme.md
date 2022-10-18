## Log

### 1. Daily Update day 1

### 2. Daily update day 2

    - POST /register : req dan res -> hapus bio dan phone
    - POST /posting : keterangan masih update harus nya insert
    - Logout belum di buat
    - DELETE /user : tidak pakai param id, pakai token nanti di be
    - GET /user/id : id diganti email
    - Fix type response yang multi -> json
    - Res /posting : pakai image url
    - Fix Res POST code -> 201
    - GET /posting/id : fix result -> 1 aja. type obj bukan array
    - GET /postings/id_posting/comments dari tag comment pindah ke posting. Di ubah menjadi show posting by id, show all comment.
    - id user pada POST dan PUT di hilangkan, nanti diganti id by ekstrak token dari be, mempermudah fe
