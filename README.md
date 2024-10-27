# ft_printf

**ft_printf**, C dilinde yazılmış bir `printf` benzeri fonksiyon kütüphanesidir. Bu proje, formatlı çıktı yapabilme yeteneği sağlar ve temel `printf` işlevselliğini yeniden oluşturmayı amaçlamaktadır.

## İçerik

- [Özellikler](#özellikler)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Fonksiyonlar](#fonksiyonlar)

## Özellikler

- `c`, `s`, `p`, `d`, `i`, `u`, `x`, `X` gibi format belirteçlerini destekler.
- Tam sayılar, karakterler, dizeler ve işaretçileri yazdırma yeteneği.
- Formatlama seçenekleri (genişlik, hassasiyet, vb.).
- Hata yönetimi ve bellek yönetimi konularında dikkat edilmiştir.

## Kurulum

Bu kütüphaneyi kendi projenizde kullanmak için aşağıdaki adımları izleyin:

1. Bu projeyi klonlayın:
   ```bash
   git clone https://github.com/kullanıcı_adı/ft_printf.git
2. Kütüphaneyi derleyin:
   ```bash
   make

## Kullanım
```#include "ft_printf.h"

int main() {
    int a = 42;
    ft_printf("Değer: %d\n", a);
    return 0;
}
```
