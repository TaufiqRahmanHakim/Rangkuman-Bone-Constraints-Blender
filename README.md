# Rangkuman-Bone-Constraints-Blender
Rangkuman Bone Constraints
Di Blender, ada fitur yang disebut "Bone Constraints" yang digunakan untuk membatasi atau mengontrol gerakan dari bones dalam rigging. Berdasarkan informasi terbaru dari [dokumentasi resmi Blender](https://docs.blender.org/manual/en/latest/animation/constraints/index.html), ada empat kategori utama dari bone constraints, yaitu:

### Motion Tracking
1. **Camera Solver Constraint**: Mengikuti gerakan kamera.
2. **Object Solver Constraint**: Mengikuti gerakan objek.
3. **Follow Track Constraint**: Mengikuti track dalam klip video.

### Transform
1. **Copy Location Constraint**: Menyalin lokasi dari bone lain.
2. **Copy Rotation Constraint**: Menyalin rotasi dari bone lain.
3. **Copy Scale Constraint**: Menyalin skala dari bone lain.
4. **Copy Transforms Constraint**: Menyalin semua transformasi dari bone lain.
5. **Limit Distance Constraint**: Membatasi jarak dari suatu titik.
6. **Limit Location Constraint**: Membatasi lokasi.
7. **Limit Rotation Constraint**: Membatasi rotasi.
8. **Limit Scale Constraint**: Membatasi skala.
9. **Maintain Volume Constraint**: Mempertahankan volume.
10. **Transformation Constraint**: Mengubah transformasi berdasarkan aturan tertentu.
11. **Transform Cache Constraint**: Menggunakan data cache untuk transformasi.

### Tracking
1. **Clamp To Constraint**: Menjaga bone agar tetap berada pada jalur atau permukaan.
2. **Damped Track Constraint**: Mengikuti target dengan meredam getaran.
3. **Inverse Kinematics Constraint**: Menggunakan algoritma IK untuk mengontrol gerakan.
4. **Locked Track Constraint**: Mengunci satu sumbu sambil mengikuti target.
5. **Spline IK Constraint**: Mengikuti spline.
6. **Stretch To Constraint**: Meregangkan untuk mencapai target.
7. **Track To Constraint**: Mengikuti target.

### Relationship
1. **Action Constraint**: Menggunakan aksi sebagai basis untuk transformasi.
2. **Armature Constraint**: Menggunakan armature lain untuk transformasi.
3. **Child Of Constraint**: Membuat bone menjadi "anak" dari objek atau bone lain.
4. **Floor Constraint**: Membatasi gerakan ke lantai atau permukaan lain.
5. **Follow Path Constraint**: Mengikuti jalur yang telah ditentukan.
6. **Pivot Constraint**: Mengubah pivot transformasi.
7. **Shrinkwrap Constraint**: Menyesuaikan bentuk berdasarkan objek target.
