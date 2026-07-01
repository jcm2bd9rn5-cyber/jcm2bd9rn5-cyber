# Contributing to My Projects

## はじめに

Shogo Taguchi のプロジェクトへの貢献をありがとうございます！🙏

このドキュメントでは、プロジェクトへの貢献方法についての基本的なガイドラインを説明しています。

---

## 🤝 貢献方法

### 1. Issue を報告する

バグを見つけた場合や改善案がある場合は、[GitHub Issues](https://github.com/jcm2bd9rn5-cyber/issues) で報告してください。

**Issue 作成時のテンプレート:**

```markdown
## タイトル
[簡潔で分かりやすいタイトル]

## 説明
[問題の詳しい説明]

## 再現手順
1. ...
2. ...

## 期待される動作
[どのようになるべきか]

## 実際の動作
[実際に起きていること]

## 環境
- OS: 
- ブラウザ: 
- その他: 
```

### 2. Pull Request を送信する

1. **フォークする**
   ```bash
   git clone https://github.com/YOUR_USERNAME/[project].git
   cd [project]
   ```

2. **ブランチを作成する**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **変更を加える**
   - コードや文書を編集
   - テストを追加（該当する場合）

4. **コミットする**
   ```bash
   git commit -m "feat: Add your feature description"
   ```

   **Commit メッセージの形式:**
   - `feat:` - 新機能
   - `fix:` - バグ修正
   - `docs:` - ドキュメント更新
   - `style:` - フォーマット変更
   - `refactor:` - コード整理
   - `perf:` - パフォーマンス改善
   - `test:` - テスト追加
   - `chore:` - その他

5. **プッシュして PR を作成**
   ```bash
   git push origin feature/your-feature-name
   ```

---

## 📋 チェックリスト

PR を提出する前に、以下を確認してください：

- [ ] コードは標準に従っている
- [ ] ドキュメントが更新されている
- [ ] テストが追加されている（該当する場合）
- [ ] 既存のテストがすべてパスしている
- [ ] コミットメッセージが明確である
- [ ] PR の説明が詳しい
- [ ] 既存の機能を壊していない

---

## 💻 コード規約

### 一般的なルール

- 読みやすさを最優先
- 適切なコメントを追加
- DRY（Don't Repeat Yourself）原則に従う
- SOLID 原則を意識する

### 言語別ガイド

**JavaScript / TypeScript:**
```javascript
// 適切な変数名
const maxRetries = 3;
const isLoading = true;

// 関数のコメント
/**
 * 説明
 * @param {type} param - パラメータの説明
 * @returns {type} 戻り値の説明
 */
function myFunction(param) {
  // 実装
}
```

**Python:**
```python
# PEP 8 に準拠
def my_function(param):
    """関数の説明
    
    Args:
        param: パラメータの説明
    
    Returns:
        戻り値の説明
    """
    pass
```

**HTML / CSS:**
```html
<!-- セマンティック HTML5 -->
<header>
  <nav>...</nav>
</header>

<!-- BEM 命名規則を使用 -->
<div class="block__element--modifier"></div>
```

```css
/* BEM 命名規則 */
.component { }
.component__element { }
.component--modifier { }

/* プロパティは論理的に整理 */
.box {
  display: flex;
  align-items: center;
  color: #333;
  font-size: 1rem;
}
```

---

## 🧪 テスト

テストは重要です！可能な限り以下を提供してください：

- **ユニットテスト** - 個別の関数・メソッドのテスト
- **統合テスト** - 複数のモジュール間のテスト
- **E2E テスト** - ユーザー視点でのテスト

---

## 📚 ドキュメント

変更内容に応じて、以下のドキュメントを更新してください：

- `README.md` - 概要と使用方法
- `CHANGELOG.md` - 変更履歴
- `ROADMAP.md` - 将来の計画
- コード内のコメント - 実装の詳細
- 関連ページ - 必要に応じて

---

## 🎯 行動指針

### すべきこと ✅

- 丁寧で尊重のあるコミュニケーション
- 質問がある場合は遠慮なく聞く
- 既存のコードベースに従う
- テストを書く
- ドキュメントを更新
- 小さく、焦点を絞った PR を作成

### してはいけないこと ❌

- 攻撃的または不敬なコメント
- 複数の無関係な機能を 1 つの PR に含める
- ドキュメントなしで機能を追加
- テストなしで複雑な変更を提出
- 大規模な未整理なコミット履歴

---

## 🔄 レビュープロセス

1. PR を提交
2. CI/CD テストが実行
3. コードレビュー
4. 修正リクエストがあれば対応
5. マージ！ 🎉

---

## 📞 質問やサポート

- **GitHub Discussions** - プロジェクトごとの Discussions
- **GitHub Issues** - バグ報告や機能リクエスト
- **メール** - jcm2bd9rn5@privaterelay.appleid.com

---

## 📖 参考資源

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Flow](https://guides.github.com/introduction/flow/)
- [Conventional Commits](https://www.conventionalcommits.org/)
- [Keep a Changelog](https://keepachangelog.com/)

---

## ⭐ 最後に

貢献してくれてありがとうございます！皆さんのフィードバックと改善提案がプロジェクトをより良くしていきます。

Happy Coding! 🚀

---

*最終更新: 2026-07-01*
