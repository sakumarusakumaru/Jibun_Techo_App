cat > README.md << 'EOF'
# Jibun_Techo_App

iOS (SwiftUI + SwiftData) のライフログアプリ。後日Androidにも展開予定。

## 環境
- Xcode 15 以降（iOS 17+）
- SwiftUI / SwiftData
- Google Drive（ストリーミング＋プロジェクトフォルダは「オフラインで使用可」推奨） 
- GitHub（mainブランチ保護）

## セットアップ（新しいMac）
1. Google Drive for Desktop をログイン
2. `DevProjects/Jibun_Techo_App` を「オフラインで使用可」にする
3. もしくはGitHubからクローン：
   ```bash
   cd ~/Google\ Drive/My\ Drive/DevProjects
   git clone https://github.com/sakumarusakumaru/Jibun_Techo_App.git
   cd Jibun_Techo_App
   open JibunTechoApp/JibunTechoApp.xcodeproj

---

**Status**: Public / Protected main / PR-based flow
