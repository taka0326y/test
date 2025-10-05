<!DOCTYPE html><html lang="ja"><head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>ケータリングカフェ｜スタバ風チェックリスト（全カテゴリ）</title>
  <meta name="theme-color" content="#006241">
  <meta property="og:title" content="ケータリングカフェ｜スタバ風チェックリスト">
  <meta property="og:description" content="カテゴリは閉じた時のみドラッグで並べ替え／数量入力／CSV入出力／印刷／取り消し（Undo）対応。カテゴリ・アイテムの追加削除、スクロール保持、軽量リレンダー追加。">
  <meta property="og:type" content="website">
  <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 32 32%22><circle cx=%2216%22 cy=%2216%22 r=%2216%22 fill=%22%23006241%22/><path d=%22M16 6c4 0 7 3 7 7s-3 7-7 7-7-3-7-7 3-7 7-7Z%22 fill=%22white%22/></svg>">
  <style>
    :root{ --sbx-green:#006241; --sbx-deep:#004c33; --sbx-cream:#f7f3e9; --sbx-paper:#fffdf6; --ink:#1f2937; --muted:#6b7280; --radius:16px; }
    *{box-sizing:border-box; transition:all .3s ease;}
    body{margin:0; font-family:ui-sans-serif,system-ui,-apple-system,"Hiragino Kaku Gothic ProN","Yu Gothic",Meiryo,sans-serif; color:var(--ink); background:linear-gradient(180deg,var(--sbx-cream),#fff)}
    header{position:sticky; top:0; z-index:10; background:linear-gradient(180deg,var(--sbx-green),var(--sbx-deep)); color:#fff; padding:16px 20px; box-shadow:0 10px 20px rgba(0,0,0,.1); display:flex; gap:16px; align-items:center; justify-content:space-between; flex-wrap:wrap}
    .title{display:flex; align-items:center; gap:12px}
    .bean{width:28px; height:28px; border-radius:50%; background:linear-gradient(135deg,#0a7350 0%,#004c33 100%); position:relative; box-shadow: inset 0 0 0 2px rgba(255,255,255,.15), 0 6px 14px rgba(0,0,0,.2)}
    .bean:before{content:""; position:absolute; top:4px; bottom:4px; left:50%; width:3px; background:#d2e7df; border-radius:2px; transform:translateX(-50%)}
    .subtitle{color:#d1fae5; font-size:12px}
    .toolbar{display:flex; gap:10px; flex-wrap:wrap}
    .btn{background:#fff; color:var(--sbx-green); border:1px solid rgba(0,0,0,.06); padding:10px 14px; border-radius:999px; font-weight:600; cursor:pointer; box-shadow:0 2px 10px rgba(0,0,0,.06); transition:.2s}
    .btn:hover{transform:translateY(-1px); box-shadow:0 6px 14px rgba(0,0,0,.12)}
    .btn.secondary{background:var(--sbx-green); color:#fff; border-color:transparent}
    .btn.ghost{background:transparent; color:#fff; border:1px solid rgba(255,255,255,.35)}
    .btn[disabled]{opacity:.45; cursor:not-allowed}
    .wrap{max-width:1100px; margin:28px auto; padding:0 16px}
    .grid{display:flex; flex-direction:column; gap:18px}

    .card{background:var(--sbx-paper); border-radius:var(--radius); padding:14px; border:1px solid rgba(0,0,0,.06); box-shadow:0 10px 24px rgba(0,0,0,.06); overflow:hidden; transition:all .3s ease;}
    .card.collapsed{max-height:40px; padding:8px 14px; box-shadow:0 2px 6px rgba(0,0,0,.1); opacity:.95;}
    .card.collapsed:hover{opacity:1; transform:scale(1.02);}
    .card.draggable{ cursor:grab; }
    .card.dragging{ opacity:.6; transform:scale(1.01); }
    .card.dragover{ outline:2px dashed rgba(0,98,65,.35); }

    .card h2{margin:0; font-size:16px; color:var(--sbx-deep); display:flex; align-items:center; justify-content:space-between; gap:10px; cursor:pointer; user-select:none}
    .left{display:flex; align-items:center; gap:8px}
    .caret{display:inline-block; width:0; height:0; border-left:6px solid transparent; border-right:6px solid transparent; border-top:8px solid var(--sbx-deep); transition:transform .2s}
    .card.collapsed .caret{transform:rotate(-90deg)}

    .list{list-style:none; padding:0; margin:8px 0 0 0; transition:all .3s ease;}
    .card.collapsed .list{display:none;}

    .row{display:flex; align-items:center; gap:10px; padding:8px 10px; border-radius:12px; border:1px dashed rgba(0,0,0,.06); margin-bottom:6px; background:#fff; transition:.2s; touch-action: pan-y;}
    .row:hover{border-color:rgba(0,98,65,.25); box-shadow:0 4px 10px rgba(0,0,0,.04)}

    input[type="checkbox"]{width:18px; height:18px; cursor:pointer; accent-color:var(--sbx-green)}
    label{cursor:pointer}
    .item{flex:1}
    .qty{width:60px; text-align:center; border:1px solid #ccc; border-radius:8px; padding:4px; font-size:13px}

    .h2-actions{display:flex; gap:6px}
    .chip{font-size:11px; padding:4px 8px; border-radius:999px; border:1px solid rgba(0,0,0,.06); background:#fff; color:var(--sbx-green); cursor:pointer}
    .chip.danger{color:#fff; background:#b91c1c; border-color:#b91c1c}

    footer{max-width:1100px; margin:20px auto 40px; padding:0 16px; color:var(--muted); font-size:12px}

    @media print{ header, footer{ display:none !important; } .card{ max-height:none !important; } .card.collapsed{ max-height:none !important; } body{ background:#fff !important; } }
  </style>
</head>
<body>
  <header>
    <div class="title">
      <span class="bean"></span>
      <div>
        <div style="font-size:18px; font-weight:800;">ケータリングカフェ｜チェックリスト</div>
        <div class="subtitle">カテゴリは閉じた時のみドラッグで並べ替え／開閉・数量入力・保存・印刷・CSV・取り消し対応（カテゴリ・アイテム追加＆削除可／スクロール保持）</div>
      </div>
    </div>
    <div class="toolbar">
      <button class="btn secondary" id="printBtn">印刷</button>
      <button class="btn" id="importBtn">CSV読み込み</button>
      <input type="file" id="csvFile" accept=".csv" style="display:none">
      <button class="btn" id="exportBtn">CSV書き出し</button>
      <button class="btn ghost" id="undoBtn" disabled>並び替えの取り消し</button>
      <button class="btn ghost" id="resetBtn">全リセット</button>
      <button class="btn" id="addCatBtn">カテゴリ追加</button>
    </div>
  </header>
  <div class="wrap"><div class="grid" id="grid"></div></div>
  <footer>※ 状態は自動保存（localStorage）。カテゴリの並び順・履歴も保存。カテゴリは閉じている時のみドラッグ可能です。</footer>
  <script>
    // ====== 初期データ ======
    const initialData={
      "運搬関係":["脚立","テーブル","台車","延長ケーブル2つ","発泡スチロール箱","ゴミ箱ゴミ袋","排水ゴムバケツ"],
      "装飾関係":["小さいメニューボード","サインボード","テーブルクロス","ディスプレイ小物"],
      "コンディメント関係":["ガムシロップ","ストロー","ホットカップ","アイスカップ","リッド","マドラー","ダスター","アルコール","サランラップ","透明水タンク"],
      "エスプレッソ関係":["エスプレッソマシン(オスカー2)","グラインダー","ピッチャー5個","タンパー","タンピングマット","レベラー","量り","卓上用ノックボックス","ブラインドフィルター","マイナスドライバー","ステンレスショットグラス2個"],
      "ドリンク関係":["コーヒー豆","抹茶粉","ほうじ茶粉","ソーダストリーム(ボトル2本)","ケトル","製氷機","小型冷蔵庫","パウダーオペレーションセット"],
      "フローズン・ソーダ関係":["グラニータマシン","フローズン原料","ソーダストリーム","炭酸ボトル","フローズンカップ","ワイドストロー"]
    };

    // ====== 永続化 ======
    const STORE_KEY='catering-checklist-v12';
    const load=()=>{try{return JSON.parse(localStorage.getItem(STORE_KEY))||{};}catch{return {}}}
    const save=s=>localStorage.setItem(STORE_KEY,JSON.stringify(s))
    const state=load()
    if(!state.checked)state.checked={}
    if(!state.qty)state.qty={}
    if(!state.collapsed)state.collapsed={}
    if(!state.catOrder)state.catOrder=Object.keys(initialData)
    if(!state.history)state.history=[]

    // 新カテゴリが初見なら末尾へ
    if(!state.catOrder.includes('フローズン・ソーダ関係')) state.catOrder.push('フローズン・ソーダ関係')
    if(state.collapsed['フローズン・ソーダ関係']===undefined) state.collapsed['フローズン・ソーダ関係']=false

    // ====== DOM 参照 ======
    const grid=document.getElementById('grid')
    const undoBtn=document.getElementById('undoBtn')

    // ====== Undo 管理 ======
    const setUndoEnabled=()=>{ undoBtn.disabled = !(state.history && state.history.length>0) }
    const snapshot=()=> JSON.parse(JSON.stringify(state.catOrder))
    const pushHistory=()=>{ state.history=state.history||[]; state.history.push(snapshot()); if(state.history.length>20) state.history.shift(); save(state); setUndoEnabled() }

    // ====== レンダー（スクロール保持 & 差分レンダー簡易対応） ======
    function render(){
      const prevY = window.scrollY
      grid.innerHTML=''
      state.catOrder.forEach(cat=>{
        const items = (initialData[cat]||[]).slice() // コピー
        const card=document.createElement('section')
        card.className='card'
        card.dataset.cat=cat
        const isCollapsed=!!state.collapsed[cat]
        if(isCollapsed) card.classList.add('collapsed','draggable'); else card.classList.add('expanded')
        card.draggable=isCollapsed

        // ドラッグハンドラ（閉時のみ）
        if(isCollapsed){
          card.addEventListener('dragstart', e=>{
            card.classList.add('dragging');
            e.dataTransfer.setData('text/cat', cat)
            pushHistory()
          })
          card.addEventListener('dragend', ()=> card.classList.remove('dragging'))
          card.addEventListener('dragover', e=>{ e.preventDefault(); card.classList.add('dragover') })
          card.addEventListener('dragleave', ()=> card.classList.remove('dragover'))
          card.addEventListener('drop', e=>{
            e.preventDefault(); card.classList.remove('dragover')
            const moving=e.dataTransfer.getData('text/cat')
            if(!moving || moving===cat) return
            const from=state.catOrder.indexOf(moving)
            const to=state.catOrder.indexOf(cat)
            if(from<0||to<0) return
            state.catOrder.splice(to,0,state.catOrder.splice(from,1)[0])
            save(state); render()
          })
        }

        // 見出し
        const h2=document.createElement('h2')
        const left=document.createElement('div'); left.className='left'
        const caret=document.createElement('span'); caret.className='caret'
        const title=document.createElement('span'); title.textContent=cat
        left.append(caret,title)

        // 操作チップ
        const actions=document.createElement('div'); actions.className='h2-actions'
        const addItemBtn=document.createElement('span'); addItemBtn.className='chip'; addItemBtn.textContent='アイテム追加'
        const renameCatBtn=document.createElement('span'); renameCatBtn.className='chip'; renameCatBtn.textContent='名称変更'
        const deleteCatBtn=document.createElement('span'); deleteCatBtn.className='chip danger'; deleteCatBtn.textContent='削除'
        actions.append(addItemBtn,renameCatBtn,deleteCatBtn)

        // 見出しクリックで開閉（スクロール保持）
        h2.onclick=(e)=>{ if(e.target.classList.contains('chip')) return; state.collapsed[cat]=!state.collapsed[cat]; save(state); render() }
        h2.append(left,actions)

        // リスト
        const ul=document.createElement('ul'); ul.className='list'
        items.forEach((label)=>{
          const li=document.createElement('li'); li.className='row'
          const id = 'cb-' + btoa(unescape(encodeURIComponent(cat+'-'+label))).replace(/=/g,'')
          const cb=document.createElement('input'); cb.type='checkbox'; cb.id=id; cb.checked=!!state.checked[label]
          cb.onchange=()=>{ state.checked[label]=cb.checked; save(state) }
          const lab=document.createElement('label'); lab.className='item'; lab.textContent=label; lab.setAttribute('for', id)
          const qty=document.createElement('input'); qty.type='number'; qty.className='qty'; qty.min='0'; qty.step='1'; qty.value=(state.qty[label] ?? 1)
          qty.onchange=()=>{ const v=parseInt(qty.value,10); state.qty[label]=(Number.isFinite(v)&&v>=0)?v:1; qty.value=state.qty[label]; save(state) }

          // 行操作（編集・削除）
          const editBtn=document.createElement('span'); editBtn.className='chip'; editBtn.textContent='編集'
          const delBtn=document.createElement('span'); delBtn.className='chip danger'; delBtn.textContent='削除'
          editBtn.onclick=()=>{
            const next=prompt('アイテム名を編集', label)
            if(!next || next.trim()===label) return
            const idx = initialData[cat].indexOf(label)
            if(idx>=0){ initialData[cat][idx]=next.trim() }
            // 付随する状態もキー移行
            state.checked[next]=state.checked[label]; delete state.checked[label]
            state.qty[next]=(state.qty[label]??1); delete state.qty[label]
            save(state); render()
          }
          delBtn.onclick=()=>{
            if(!confirm(`「${label}」を削除しますか？`)) return
            initialData[cat]=initialData[cat].filter(x=>x!==label)
            delete state.checked[label]; delete state.qty[label]
            save(state); render()
          }

          const ops=document.createElement('div'); ops.className='h2-actions'; ops.append(editBtn,delBtn)
          li.append(cb,lab,qty,ops); ul.append(li)
        })

        // ボタンクリック実装
        addItemBtn.onclick=()=>{
          const name = prompt('追加するアイテム名を入力')
          if(!name || !name.trim()) return
          initialData[cat]=initialData[cat]||[]
          initialData[cat].push(name.trim())
          if(state.qty[name]===undefined) state.qty[name]=1
          save(state); render()
        }
        renameCatBtn.onclick=()=>{
          const next=prompt('カテゴリ名を編集', cat)
          if(!next || next.trim()===cat) return
          const newName=next.trim()
          // データ移行
          initialData[newName]=initialData[cat]||[]
          delete initialData[cat]
          const idx=state.catOrder.indexOf(cat); if(idx>=0) state.catOrder[idx]=newName
          state.collapsed[newName]=state.collapsed[cat]; delete state.collapsed[cat]
          save(state); render()
        }
        deleteCatBtn.onclick=()=>{
          if(!confirm(`カテゴリ「${cat}」を削除しますか？`)) return
          // 関連状態クリア
          ;(initialData[cat]||[]).forEach(l=>{ delete state.checked[l]; delete state.qty[l] })
          delete initialData[cat]
          state.catOrder=state.catOrder.filter(c=>c!==cat)
          delete state.collapsed[cat]
          save(state); render()
        }

        card.append(h2,ul); grid.append(card)
      })
      setUndoEnabled()
      // スクロール位置を戻す
      window.scrollTo({top: prevY, behavior:'instant' in window? 'instant':'auto'})
    }

    render()

    // 末尾ドロップ
    grid.addEventListener('dragover', e=> e.preventDefault())
    grid.addEventListener('drop', e=>{
      const moving=e.dataTransfer.getData('text/cat')
      if(!moving) return
      const from=state.catOrder.indexOf(moving)
      if(from<0) return
      pushHistory()
      state.catOrder.push(state.catOrder.splice(from,1)[0])
      save(state); render()
    })

    // Undo
    undoBtn.addEventListener('click', ()=>{
      if(!state.history || state.history.length===0) return
      const prev=state.history.pop()
      if(Array.isArray(prev) && prev.length){ state.catOrder=prev; save(state); render() }
      setUndoEnabled()
    })

    // 追加: カテゴリ追加
    document.getElementById('addCatBtn').onclick=()=>{
      const name=prompt('新しいカテゴリ名を入力')
      if(!name || !name.trim()) return
      const cat=name.trim()
      if(initialData[cat]){ alert('同名カテゴリが存在します'); return }
      initialData[cat]=[]
      state.catOrder.push(cat)
      state.collapsed[cat]=false
      save(state); render()
    }

    // 既存: 各種ユーティリティ
    document.getElementById('printBtn').onclick=()=>window.print()
    document.getElementById('resetBtn').onclick=()=>{if(confirm('全リセットしますか？')){localStorage.removeItem(STORE_KEY);location.reload()}}

    // CSV エクスポート
    document.getElementById('exportBtn').onclick=()=>{
      const lines=['カテゴリ,アイテム,チェック,数量']
      state.catOrder.forEach(cat=>{
        const items=initialData[cat]||[]
        items.forEach(label=>{
          const esc=s=>'"'+String(s).replaceAll('"','""')+'"'
          lines.push([esc(cat),esc(label),state.checked[label]?1:0,(state.qty[label]??1)].join(','))
        })
      })
      const blob=new Blob([lines.join('\n')],{type:'text/csv;charset=utf-8;'})
      const a=document.createElement('a');a.href=URL.createObjectURL(blob);a.download='チェックリスト.csv';a.click()
    }

    // CSV インポート
    const csvFile=document.getElementById('csvFile')
    document.getElementById('importBtn').onclick=()=>csvFile.click()
    csvFile.onchange=e=>{
      const file=e.target.files[0]; if(!file) return
      const r=new FileReader(); r.onload=()=>loadCsv(r.result); r.readAsText(file,'utf-8'); e.target.value=''
    }

    function parseCsv(t){
      const r=[];let i=0,f='',row=[],q=false
      while(i<t.length){const c=t[i]
        if(q){ if(c=='"'){ if(t[i+1]=='"'){f+='"'; i+=2; continue} q=false; i++; continue } else { f+=c; i++; continue } }
        else{ if(c=='"'){ q=true; i++; continue }
          if(c==','){ row.push(f); f=''; i++; continue }
          if(c=='\n'||c=='\r'){ if(f!==''||row.length>0){ row.push(f); r.push(row); row=[]; f='' } i++; continue }
          f+=c; i++ }
      }
      if(f!==''||row.length>0){ row.push(f); r.push(row) }
      return r.filter(r=>r.length>0)
    }
    function loadCsv(t){
      const rows=parseCsv(t); if(!rows.length) return alert('CSVが空です')
      const h=rows[0].map(s=>s.trim())
      const ic=h.indexOf('アイテム'); const ck=h.indexOf('チェック'); const qy=h.indexOf('数量'); const cc=h.indexOf('カテゴリ')
      if(ic<0) return alert('アイテム列が必要です')
      rows.slice(1).forEach(cols=>{
        const l=(cols[ic]||'').trim(); if(!l) return
        const cName=(cc>=0?(cols[cc]||'').trim():null)
        if(cName){ // 未存在カテゴリは自動作成
          if(!initialData[cName]){ initialData[cName]=[]; state.catOrder.push(cName); state.collapsed[cName]=false }
          if(!initialData[cName].includes(l)) initialData[cName].push(l)
        }
        if(ck>=0){ const c=(cols[ck]||'').trim(); state.checked[l]=(c==='1'||c.toLowerCase()==='true') }
        if(qy>=0){ const q=parseInt((cols[qy]||'1').trim(),10); state.qty[l]=(Number.isFinite(q)&&q>=0)?q:1 }
      })
      save(state); render(); alert('CSVを読み込みました')
    }
  </script>
</body>
</html>
