# FORM PENDAFTARAN OSIS

This project contains an HTML-based registration form for OSIS (Organisasi Siswa Intra Sekolah). The form collects user information and is styled with inline CSS for simplicity. Below is an overview of the project structure and features.

## Features
- **Responsive Design (Commented Out)**: There is a commented-out media query for small screen devices (max-width: 600px) to provide basic responsiveness.
- **Form Fields**:
  - Nama Lengkap (Full Name)
  - Nama Panggilan (Nickname)
  - Tempat Tanggal Lahir (Date of Birth)
  - Jenis Kelamin (Gender) with radio buttons for "Laki-Laki" (Male) and "Perempuan" (Female)
  - Nomor Telepon (Phone Number)
  - Jurusan (Field of Study) with options for "IPA," "IPS," and "BAHASA"
  - Agama (Religion) with a dropdown list
  - Hobi (Hobby) with checkboxes for options like "Membaca Buku" (Reading), "Menulis" (Writing), and others
  - Alasan/Motivasi untuk mendaftar (Reason/Motivation for registering) with a large text area
  - Foto 3X4 (Photo) upload field
- **Submission and Reset Buttons**: Includes a submit button (`Daftar`) and a reset button (`Reset`).

## File Structure
- `index.html`: Contains the HTML structure for the form, including inline CSS for styling.

## How to Use
1. Clone this repository to your local machine:

   ```bash
   git clone <repository_url>
   ```
2. Open the `index.html` file in any web browser to view the form.
3. Fill out the form fields and submit the form.

## Screenshot
Below is an example screenshot of the registration form:

<img src="/FormPendaftaranOsis.png" alt="Form Pendaftaran Osis" width="40%" height="40%">

## Future Enhancements
- Add JavaScript validation for form fields.
- Improve responsiveness for mobile devices.
- Use external CSS for better maintainability.
- Store form submissions in a database or display them on a confirmation page.

## License
This project is licensed under the [MIT License](https://github.com/wyattmatt/Entrance-Project/blob/main/LICENSE). Feel free to use and modify the code as needed.
