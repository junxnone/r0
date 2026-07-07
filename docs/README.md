# Review

> 基于 GitHub Issues 的 Wiki

<div class="homepage-search">
  <input type="search" placeholder="🔍 搜索文章..." class="search-input" />
  <div class="search-results-panel"></div>
</div>

## 📚 按标签浏览

<div class="tag-buttons">
  <a href="#/tags/AI" class="tag-button">AI <span class="tag-count">2</span></a>
  <a href="#/tags/%E9%97%AE%E9%A2%98" class="tag-button">问题 <span class="tag-count">2</span></a>
  <a href="#/tags/VibeCoding" class="tag-button">VibeCoding <span class="tag-count">1</span></a>
  <a href="#/tags/%E4%B8%87%E7%89%A9" class="tag-button">万物 <span class="tag-count">1</span></a>
  <a href="#/tags/%E4%B8%AA%E4%BA%BA%E8%83%BD%E5%8A%9B" class="tag-button">个人能力 <span class="tag-count">1</span></a>
  <a href="#/tags/%E4%BA%BA%E7%94%9F" class="tag-button">人生 <span class="tag-count">1</span></a>
  <a href="#/tags/%E4%BF%A1%E6%81%AF" class="tag-button">信息 <span class="tag-count">1</span></a>
  <a href="#/tags/%E4%BF%AE%E8%BA%AB" class="tag-button">修身 <span class="tag-count">1</span></a>
  <a href="#/tags/%E5%85%B3%E7%B3%BB" class="tag-button">关系 <span class="tag-count">1</span></a>
  <a href="#/tags/%E5%8A%BF" class="tag-button">势 <span class="tag-count">1</span></a>
  <a href="#/tags/%E5%8D%B1%E6%9C%BA" class="tag-button">危机 <span class="tag-count">1</span></a>
  <a href="#/tags/%E5%8F%91%E7%8E%B0" class="tag-button">发现 <span class="tag-count">1</span></a>
  <a href="#/tags/%E5%8F%98%E7%8E%B0" class="tag-button">变现 <span class="tag-count">1</span></a>
  <a href="#/tags/%E5%B1%82%E7%BA%A7" class="tag-button">层级 <span class="tag-count">1</span></a>
  <a href="#/tags/%E6%8A%80%E8%83%BD" class="tag-button">技能 <span class="tag-count">1</span></a>
  <a href="#/tags/%E6%9B%BF%E4%BB%A3" class="tag-button">替代 <span class="tag-count">1</span></a>
  <a href="#/tags/%E6%9D%A0%E6%9D%86" class="tag-button">杠杆 <span class="tag-count">1</span></a>
  <a href="#/tags/%E6%BA%AF%E6%BA%90" class="tag-button">溯源 <span class="tag-count">1</span></a>
  <a href="#/tags/%E7%9F%A5%E8%AF%86" class="tag-button">知识 <span class="tag-count">1</span></a>
  <a href="#/tags/%E7%A0%94%E7%A9%B6" class="tag-button">研究 <span class="tag-count">1</span></a>
  <a href="#/tags/%E7%B3%BB%E7%BB%9F" class="tag-button">系统 <span class="tag-count">1</span></a>
  <a href="#/tags/%E7%BC%93%E5%AD%98" class="tag-button">缓存 <span class="tag-count">1</span></a>
  <a href="#/tags/%E8%84%91" class="tag-button">脑 <span class="tag-count">1</span></a>
  <a href="#/tags/%E8%B7%AF" class="tag-button">路 <span class="tag-count">1</span></a>
  <a href="#/tags/%E9%A3%9F%E5%93%81" class="tag-button">食品 <span class="tag-count">1</span></a>
  <a href="#/tags/%E9%A9%B1%E5%8A%A8" class="tag-button">驱动 <span class="tag-count">1</span></a>
</div>

## [📜 历史记录](/history)

<style>
.homepage-search { max-width: 600px; margin: 2rem auto; padding: 0 1rem; position: relative; }
.homepage-search .search-input { width: 100%; padding: 0.8rem 1.2rem; font-size: 1rem; border: 2px solid #e0e0e0; border-radius: 8px; outline: none; transition: all 0.3s ease; box-shadow: 0 2px 4px rgba(0,0,0,0.05); }
.homepage-search .search-input:focus { border-color: var(--theme-color, #42b983); box-shadow: 0 4px 12px rgba(66, 185, 131, 0.15); }
.search-results-panel { position: absolute; top: 100%; left: 1rem; right: 1rem; margin-top: 0.5rem; background: white; border: 2px solid var(--theme-color, #42b983); border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.15); max-height: 400px; overflow-y: auto; z-index: 1000; display: none; }
.search-results-panel.active { display: block; }
.search-result-item { padding: 0.8rem 1.2rem; border-bottom: 1px solid #f0f0f0; cursor: pointer; transition: background 0.2s ease; }
.search-result-item:hover { background: #f5f5f5; }
.search-result-item:last-child { border-bottom: none; }
.search-result-title { font-weight: 600; color: var(--theme-color, #42b983); margin-bottom: 0.3rem; }
.search-result-content { font-size: 0.85rem; color: #666; line-height: 1.4; }
.search-no-results { padding: 1rem 1.2rem; text-align: center; color: #999; }
.tag-buttons { display: flex; flex-wrap: wrap; gap: 0.8rem; margin-bottom: 2rem; }
.tag-button { display: inline-flex; align-items: center; padding: 0.6rem 1.2rem; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white !important; border-radius: 8px; text-decoration: none; font-weight: 500; transition: all 0.3s ease; box-shadow: 0 2px 4px rgba(0,0,0,0.1); }
.tag-button:hover { transform: translateY(-2px); box-shadow: 0 4px 12px rgba(0,0,0,0.2); }
.tag-button .tag-count { margin-left: 0.5rem; background: rgba(255,255,255,0.3); padding: 0.2rem 0.5rem; border-radius: 12px; font-size: 0.85rem; }
.tag-button.special { background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); font-size: 1.1rem; padding: 0.8rem 1.5rem; }
@media (max-width: 768px) { .tag-buttons { gap: 0.5rem; } .tag-button { padding: 0.5rem 1rem; font-size: 0.9rem; } }
</style>