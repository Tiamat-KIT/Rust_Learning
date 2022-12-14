# Rustの実行
### Rustプログラムのコンパイル

```bash
rustc コンパイルしたいRustプログラムファイル
```

### コンパイルしたプログラムの実行
```bash
./元のプログラムファイル名.exe
```

# Cargo を使用してプロジェクトを作成

### Cargoコマンドでプロジェクト作成
```bash
cargo new プロジェクト名
```

### Cargo を使用してプログラムをビルドして実行する

```bash
cd 作成したプロジェクト名
cargo run
```

# プログラムの文法
```rust
fn 関数名() {

}
```

Rustのプログラムは必ずmain関数を持つ必要がある。main 関数内のコードは、常に、Rust プログラムで最初に実行されるコード

### 文字列表示
println! マクロが呼び出す。 println! マクロには、画面または "標準出力" に表示される 1 つ以上の入力引数が必要。

```rust
println!("Hello, world!");
```

中かっこ {} とその他の値のインスタンスが含まれるテキスト文字列を含む引数のリストを指定して println! マクロを呼び出します。 println! マクロにより、テキスト文字列内の中かっこ {} の各インスタンスが、リスト内の次の引数の値に置き換えられます。

```rust
println!("The first letter of the English alphabet is {} and the last letter is {}.", 'A', 'Z');
```
と記述すると、
```bash
The first letter of the English alphabet is A and the last letter is Z.
```
と出力される

### 変数宣言
```rust
let num;
```
or
```rust
let a_number = 10;
```

