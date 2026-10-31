# N2_Quiz
N2 JLPT Quiz - Multi exam structure

Files:
- index.html: giao dien quiz va dropdown chon de thi
- questions-n2-t7-2026.js: du lieu de N2 thang 7/2026

Cach chay:
1. Giu index.html va cac file questions-*.js trong cung mot thu muc.
2. Mo index.html bang Chrome/Edge/Firefox.

Them de thi moi:
1. Copy file questions-n2-t7-2026.js va doi ten, vi du questions-n2-t12-2026.js.
2. Trong file moi, sua id/title va thay mang questions bang du lieu de moi.
3. File moi can dang ky vao window.JLPT_EXAMS bang mau:

window.JLPT_EXAMS = window.JLPT_EXAMS || [];
window.JLPT_EXAMS.push({
  id: 'N2_T12_2026',
  title: 'JLPT N2 - Thang 12/2026',
  questions: [ /* cac cau hoi */ ]
});

4. Mo index.html, them script tag moi ngay sau script hien tai:
<script src="questions-n2-t12-2026.js"></script>
5. Reload trang. De moi se tu dong xuat hien trong dropdown De thi.

Moi cau hoi co the co cac truong: c, p, passageId, passage, q, o, a, e, om.
- passage/passageId: bai doc dung chung cho cac cau doc hieu.
- om: mang 4 phan tu, giai thich nghia tung lua chon bang tieng Viet.
