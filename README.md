# pix2pix_cv_mipt_2022
Repo of CV semester project by Julia SMolkina

Я использую модель pix2pix, Для обучеия использовалось 3 датасета (аниме,CHUNK. celebA). Валидация тже проходила на этих датасетах, а также на моей фотографии ( предварительно были сгенерированы скетчи недостоющим картинкам)

Особенностью данной реализации, можно считать, что на вход попадают сдвоенные картинки (фото+скетч), поэтому я дописала часть которая соединяет картинки вместе. Также из-за того, что выши картинки могут лежать в разных папках была дописана часть сопоставляющая картинки из разных репозиторие с одинаковым паттерном в имен ( например f-011-5.jpg и f2-011-5.jpg). В коде также есть генератор скетчей.

