# LSTM Prediksi Dinamika Limbah Plastik — Mingguan

Model LSTM Bidirectional untuk memprediksi konsentrasi plastik laut
menggunakan data hidrodinamika dengan resolusi **mingguan**.

## Metrik Evaluasi
| Metrik | Nilai |
|--------|-------|
| RMSE | 52.17 partikel/m³ |
| MAE  | 42.48 partikel/m³ |
| MAPE | 11.41 % |
| R²   | 0.3588 |

## Struktur
- Window : 12 minggu (~84 hari)
- Horizon: 4 minggu ke depan (~28 hari)
- Fitur  : 15 variabel hidrodinamika
