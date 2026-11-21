# AI çalışma kuralları

## Commit ve sürüm kaydı

- Her commit'ten önce `CHANGELOG.md` dosyasının en üstüne o commit için yeni bir sürüm kaydı ekle. Changelog değişikliğini ilgili değişikliklerle aynı commit'e dahil et. Bu kural dokümantasyon, düzeltme ve geri alma commit'leri için de geçerlidir.
- Her kayıtta `MAJOR.MINOR.PATCH` biçiminde benzersiz bir sürüm numarası ve commit'te nelerin değiştiğini anlatan kısa maddeler bulunmalı. Sürümü son kayıttan ilerlet. Yeni özellik için minor, düzeltme veya dokümantasyon için patch, geriye uyumluluğu bozan değişiklik için major artır.
- Commit atmadan önce changelog kaydını commit'e girecek değişikliklerle karşılaştır. Önceki kayıtları sakla ve en yeni sürümü en üstte tut.
