# 起動手順（Claude向け）

ユーザーがこのリポジトリのURLを渡して「自分軸ファインダーを始めて」と依頼したときは、次の手順で進める。

1. 次のURLをWeb取得で読み込む。これがスキル本体（SKILL.md）である。
   https://raw.githubusercontent.com/s4qr-tech/no-dakyou-job/main/skills/no-dakyou-job/SKILL.md
2. SKILL.md の指示に、そのまま従う。SKILL.md が参照する相対パスは、次のURLを基準に読み替えて、必要になった時点で取得する（最初に全部は読まない）。
   基準URL：https://raw.githubusercontent.com/s4qr-tech/no-dakyou-job/main/skills/no-dakyou-job/
   - references/questions.md（質問集）
   - references/industry-map.md（業界別の観点）
   - references/handoff-schema.md（jiku-profile.md の書式）
   - assets/design/（tokens.css、components.css、design-rules.md、templates/）
3. 取得に失敗したら、推測で進めず、その旨をユーザーに伝える。代替手段は、README の「ZIPで入れる」を案内する。
4. SKILL.md の「成果物の作成前に仕様を確認する」ルールは、URL経由でも同じように守る。
