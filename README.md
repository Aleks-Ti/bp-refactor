# bp-refactor

## Навигация

- [команды для запуска проекта и дебага](#shugarcommand)

## ShugarCommand

```rust
// `-- --nocapture` позволяет не прятать вывод в терминал (println!() и подобное)
cargo test -- --nocapture
// конкретный тест для запуска можно указать сразу после `test`
cargo test test_all -- --nocapture
// запуск бинарника; в файле с локами те же данные, что и в тестах, - бинарь
// должен остаться работоспособным
cargo run example.log 
```
