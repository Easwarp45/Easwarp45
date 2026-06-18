<div align="center">
  <a href="https://easwar-profile.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/View%20My%20Interactive%20Profile-00d4ff?style=for-the-badge&logo=vercel&logoColor=black" alt="Interactive Profile" />
  </a>
</div>

<br />

```aura width=820 height=200
<div style={{
  width: '820px', height: '200px',
  background: 'linear-gradient(135deg, #0a0a0f 0%, #0d1117 60%, #0a0a0f 100%)',
  display: 'flex', flexDirection: 'column',
  alignItems: 'center', justifyContent: 'center',
  fontFamily: 'Inter',
}}>
  <style>{`
    @keyframes pulse-glow { 0%,100%{opacity:0.3} 50%{opacity:1} }
    @keyframes flicker { 0%,94%,100%{opacity:1} 95%{opacity:0.5} 98%{opacity:0.85} }
    #d1{animation:pulse-glow 2s ease-in-out infinite}
    #d2{animation:pulse-glow 2s ease-in-out 0.7s infinite}
    #nametext{animation:flicker 5s ease-in-out infinite}
  `}</style>
  <div style={{ display: 'flex', alignItems: 'center', gap: '8px', marginBottom: '14px' }}>
    <div id="d1" style={{ width: '5px', height: '5px', borderRadius: '50%', background: '#00d4ff' }} />
    <div style={{ fontSize: '9px', letterSpacing: '4px', color: '#00d4ff66' }}>SYSTEM ONLINE</div>
    <div id="d2" style={{ width: '5px', height: '5px', borderRadius: '50%', background: '#00d4ff' }} />
  </div>
  <div id="nametext" style={{
    fontSize: '44px', fontWeight: '800', letterSpacing: '-1px',
    background: 'linear-gradient(90deg, #ffffff 0%, #00d4ff 55%, #7c3aed 100%)',
    backgroundClip: 'text', color: 'transparent', display: 'flex',
  }}>
    EASWARAMURTHY P
  </div>
  <div style={{ display: 'flex', alignItems: 'center', gap: '14px', marginTop: '12px' }}>
    <div style={{ fontSize: '12px', letterSpacing: '3px', color: '#8892a4' }}>FULL STACK DEV</div>
    <div style={{ width: '4px', height: '4px', borderRadius: '50%', background: '#7c3aed' }} />
    <div style={{ fontSize: '12px', letterSpacing: '3px', color: '#8892a4' }}>FLUTTER DEV</div>
    <div style={{ width: '4px', height: '4px', borderRadius: '50%', background: '#7c3aed' }} />
    <div style={{ fontSize: '12px', letterSpacing: '3px', color: '#8892a4' }}>DATA ANALYTICS</div>
  </div>
</div>
```

```aura width=820 height=260
<div style={{
  width: '820px', height: '260px',
  background: '#0d1117',
  display: 'flex', flexDirection: 'row',
  fontFamily: 'Inter',
}}>
  <style>{`
    @keyframes blink { 0%,100%{opacity:1} 50%{opacity:0} }
    #cursor{animation:blink 1.1s step-end infinite}
  `}</style>
  <div style={{ flex: '1', background: '#0a0a0f', display: 'flex', flexDirection: 'column', borderRight: '1px solid #1e2430' }}>
    <div style={{ height: '32px', background: '#161b22', display: 'flex', alignItems: 'center', padding: '0 14px', gap: '7px', borderBottom: '1px solid #1e2430' }}>
      <div style={{ width: '10px', height: '10px', borderRadius: '50%', background: '#ff5f57' }} />
      <div style={{ width: '10px', height: '10px', borderRadius: '50%', background: '#febc2e' }} />
      <div style={{ width: '10px', height: '10px', borderRadius: '50%', background: '#28c840' }} />
      <div style={{ marginLeft: '10px', fontSize: '10px', color: '#484f58', letterSpacing: '1px' }}>eswar@dev ~ about.sh</div>
    </div>
    <div style={{ padding: '16px 20px', display: 'flex', flexDirection: 'column', gap: '7px' }}>
      <div style={{ display: 'flex', gap: '8px' }}>
        <div style={{ fontSize: '11.5px', color: '#28c840', fontWeight: '700' }}>$</div>
        <div style={{ fontSize: '11.5px', color: '#00d4ff' }}>whoami</div>
      </div>
      <div style={{ fontSize: '11.5px', color: '#8892a4', paddingLeft: '16px' }}>Easwaramurthy P — Final Year CSE @ Kings Engineering College, Chennai</div>
      <div style={{ display: 'flex', gap: '8px', marginTop: '4px' }}>
        <div style={{ fontSize: '11.5px', color: '#28c840', fontWeight: '700' }}>$</div>
        <div style={{ fontSize: '11.5px', color: '#00d4ff' }}>cat focus.txt</div>
      </div>
      <div style={{ fontSize: '11.5px', color: '#8892a4', paddingLeft: '16px' }}>→  Full Stack Web Development</div>
      <div style={{ fontSize: '11.5px', color: '#8892a4', paddingLeft: '16px' }}>→  Flutter and Dart Mobile Apps</div>
      <div style={{ fontSize: '11.5px', color: '#8892a4', paddingLeft: '16px' }}>→  Data Analytics and Visualization</div>
      <div style={{ fontSize: '11.5px', color: '#8892a4', paddingLeft: '16px' }}>→  UI/UX Design</div>
      <div style={{ display: 'flex', gap: '8px', alignItems: 'center', marginTop: '4px' }}>
        <div style={{ fontSize: '11.5px', color: '#28c840', fontWeight: '700' }}>$</div>
        <div id="cursor" style={{ width: '7px', height: '13px', background: '#00d4ff', borderRadius: '1px' }} />
      </div>
    </div>
  </div>
  <div style={{ width: '240px', display: 'flex', flexDirection: 'column', padding: '20px 22px', gap: '12px' }}>
    <div style={{ fontSize: '9px', letterSpacing: '3px', color: '#484f58' }}>// identity</div>
    <div style={{ display: 'flex', alignItems: 'center', gap: '10px' }}>
      <div style={{ fontSize: '14px' }}>📍</div>
      <div style={{ fontSize: '11px', color: '#8892a4' }}>Chennai, India</div>
    </div>
    <div style={{ display: 'flex', alignItems: 'center', gap: '10px' }}>
      <div style={{ fontSize: '14px' }}>🎓</div>
      <div style={{ fontSize: '11px', color: '#8892a4' }}>B.E. Computer Science</div>
    </div>
    <div style={{ display: 'flex', alignItems: 'center', gap: '10px' }}>
      <div style={{ fontSize: '14px' }}>💼</div>
      <div style={{ fontSize: '11px', color: '#8892a4' }}>Open to Opportunities</div>
    </div>
    <div style={{ display: 'flex', alignItems: 'center', gap: '10px' }}>
      <div style={{ fontSize: '14px' }}>⚡</div>
      <div style={{ fontSize: '11px', color: '#8892a4' }}>Building Kanakku App</div>
    </div>
    <div style={{ height: '1px', background: '#1e2430', marginTop: '4px' }} />
    <div style={{ fontSize: '9px', letterSpacing: '3px', color: '#484f58' }}>// philosophy</div>
    <div style={{ fontSize: '12px', color: '#00d4ff88', fontStyle: 'italic' }}>"Build. Learn. Improve. Repeat."</div>
  </div>
</div>
```

---

## 🛠️ Tech Stack

```aura width=820 height=300
<div style={{
  width: '820px', height: '300px',
  background: '#0d1117',
  display: 'flex', flexDirection: 'column',
  padding: '20px 24px', gap: '16px',
  fontFamily: 'Inter',
}}>
  <div style={{ display: 'flex', flexDirection: 'column', gap: '8px' }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
      <div style={{ width: '6px', height: '6px', borderRadius: '50%', background: '#00d4ff' }} />
      <div style={{ fontSize: '9px', letterSpacing: '3px', color: '#00d4ff88' }}>FRONTEND</div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'row', gap: '6px' }}>
      {['React','TypeScript','JavaScript','HTML5','CSS3','Tailwind CSS','Vite'].map((t,i) => (
        <div key={i} style={{ fontSize: '11px', padding: '4px 10px', background: '#00d4ff11', border: '1px solid #00d4ff33', color: '#00d4ffcc', borderRadius: '4px' }}>{t}</div>
      ))}
    </div>
  </div>
  <div style={{ display: 'flex', flexDirection: 'column', gap: '8px' }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
      <div style={{ width: '6px', height: '6px', borderRadius: '50%', background: '#7c3aed' }} />
      <div style={{ fontSize: '9px', letterSpacing: '3px', color: '#7c3aed88' }}>BACKEND AND DATABASE</div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'row', gap: '6px' }}>
      {['Node.js','Express.js','REST API','Supabase','PostgreSQL'].map((t,i) => (
        <div key={i} style={{ fontSize: '11px', padding: '4px 10px', background: '#7c3aed11', border: '1px solid #7c3aed33', color: '#7c3aedcc', borderRadius: '4px' }}>{t}</div>
      ))}
    </div>
  </div>
  <div style={{ display: 'flex', flexDirection: 'column', gap: '8px' }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
      <div style={{ width: '6px', height: '6px', borderRadius: '50%', background: '#28c840' }} />
      <div style={{ fontSize: '9px', letterSpacing: '3px', color: '#28c84088' }}>MOBILE</div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'row', gap: '6px' }}>
      {['Flutter','Dart','Capacitor'].map((t,i) => (
        <div key={i} style={{ fontSize: '11px', padding: '4px 10px', background: '#28c84011', border: '1px solid #28c84033', color: '#28c840cc', borderRadius: '4px' }}>{t}</div>
      ))}
    </div>
  </div>
  <div style={{ display: 'flex', flexDirection: 'column', gap: '8px' }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
      <div style={{ width: '6px', height: '6px', borderRadius: '50%', background: '#febc2e' }} />
      <div style={{ fontSize: '9px', letterSpacing: '3px', color: '#febc2e88' }}>DATA AND TOOLS</div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'row', gap: '6px' }}>
      {['Python','Pandas','NumPy','Power BI','Figma','Git','VS Code'].map((t,i) => (
        <div key={i} style={{ fontSize: '11px', padding: '4px 10px', background: '#febc2e11', border: '1px solid #febc2e33', color: '#febc2ecc', borderRadius: '4px' }}>{t}</div>
      ))}
    </div>
  </div>
</div>
```

---

## 🚀 Featured Projects

```aura width=820 height=280
<div style={{
  width: '820px', height: '280px',
  background: '#0d1117',
  display: 'flex', flexDirection: 'row',
  fontFamily: 'Inter',
}}>
  <style>{`
    @keyframes glow { 0%,100%{opacity:0.4} 50%{opacity:1} }
    #a0{animation:glow 3.5s ease-in-out infinite}
    #a1{animation:glow 3.5s ease-in-out 1.2s infinite}
    #a2{animation:glow 3.5s ease-in-out 2.4s infinite}
  `}</style>
  <div style={{ flex: '1', display: 'flex', flexDirection: 'column', padding: '0 20px 20px', gap: '10px', borderRight: '1px solid #1e2430' }}>
    <div id="a0" style={{ height: '2px', background: 'linear-gradient(90deg, #00d4ff88, transparent)', marginBottom: '10px' }} />
    <div style={{ fontSize: '22px' }}>💰</div>
    <div style={{ fontSize: '14px', fontWeight: '700', color: '#e6edf3' }}>Kanakku</div>
    <div style={{ fontSize: '11px', color: '#8892a4', lineHeight: '1.6' }}>Personal finance tracker with spend analytics, insights dashboard, and native Android via Capacitor.</div>
    <div style={{ display: 'flex', flexDirection: 'row', gap: '5px', marginTop: 'auto' }}>
      {['React','TypeScript','Tailwind','Supabase'].map((t,i)=>(
        <div key={i} style={{ fontSize: '9px', padding: '2px 7px', background: '#00d4ff11', border: '1px solid #00d4ff33', color: '#00d4ffcc', borderRadius: '3px' }}>{t}</div>
      ))}
    </div>
  </div>
  <div style={{ flex: '1', display: 'flex', flexDirection: 'column', padding: '0 20px 20px', gap: '10px', borderRight: '1px solid #1e2430' }}>
    <div id="a1" style={{ height: '2px', background: 'linear-gradient(90deg, #7c3aed88, transparent)', marginBottom: '10px' }} />
    <div style={{ fontSize: '22px' }}>🔐</div>
    <div style={{ fontSize: '14px', fontWeight: '700', color: '#e6edf3' }}>Secur Pass</div>
    <div style={{ fontSize: '11px', color: '#8892a4', lineHeight: '1.6' }}>Password generator and account security utility with a clean, minimal interface.</div>
    <div style={{ display: 'flex', flexDirection: 'row', gap: '5px', marginTop: 'auto' }}>
      {['HTML','CSS','JavaScript'].map((t,i)=>(
        <div key={i} style={{ fontSize: '9px', padding: '2px 7px', background: '#7c3aed11', border: '1px solid #7c3aed33', color: '#7c3aedcc', borderRadius: '3px' }}>{t}</div>
      ))}
    </div>
  </div>
  <div style={{ flex: '1', display: 'flex', flexDirection: 'column', padding: '0 20px 20px', gap: '10px' }}>
    <div id="a2" style={{ height: '2px', background: 'linear-gradient(90deg, #28c84088, transparent)', marginBottom: '10px' }} />
    <div style={{ fontSize: '22px' }}>📊</div>
    <div style={{ fontSize: '14px', fontWeight: '700', color: '#e6edf3' }}>Data Analytics</div>
    <div style={{ fontSize: '11px', color: '#8892a4', lineHeight: '1.6' }}>NLP sentiment analysis, Iris classification, NYC taxi analysis, and data visualization reports.</div>
    <div style={{ display: 'flex', flexDirection: 'row', gap: '5px', marginTop: 'auto' }}>
      {['Python','Pandas','NumPy','Power BI'].map((t,i)=>(
        <div key={i} style={{ fontSize: '9px', padding: '2px 7px', background: '#28c84011', border: '1px solid #28c84033', color: '#28c840cc', borderRadius: '3px' }}>{t}</div>
      ))}
    </div>
  </div>
</div>
```

---

## 📈 GitHub Stats

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Easwarp45&show_icons=true&theme=tokyonight&hide_border=true"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Easwarp45&layout=compact&theme=tokyonight&hide_border=true"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Easwarp45&theme=tokyonight&hide_border=true"/>
</div>

---

## 🎯 2026 Goals

```aura width=820 height=120
<div style={{
  width: '820px', height: '120px',
  background: '#0d1117',
  display: 'flex', flexDirection: 'row', alignItems: 'center',
  padding: '0 20px', gap: '12px',
  fontFamily: 'Inter',
}}>
  {[
    ['🚀','Full Stack Apps'],
    ['📱','Mobile Apps'],
    ['⚡','Backend and APIs'],
    ['📊','Data Analytics'],
    ['☁️','Cloud and DevOps'],
    ['🤝','Open Source'],
  ].map(([icon, goal], i) => (
    <div key={i} style={{
      flex: '1', display: 'flex', flexDirection: 'column',
      alignItems: 'center', justifyContent: 'center', gap: '6px',
      background: '#0a0a0f', border: '1px solid #1e2430',
      borderRadius: '6px', padding: '12px 6px', height: '70px',
    }}>
      <div style={{ fontSize: '18px' }}>{icon}</div>
      <div style={{ fontSize: '9px', color: '#8892a4', textAlign: 'center' }}>{goal}</div>
    </div>
  ))}
</div>
```

---

## 📬 Connect With Me

```aura width=820 height=80
<div style={{
  width: '820px', height: '80px',
  background: '#0d1117',
  display: 'flex', flexDirection: 'row',
  alignItems: 'center', justifyContent: 'center', gap: '16px',
  fontFamily: 'Inter',
}}>
  {[
    { label: 'Website', color: '#00d4ff', short: 'WEB' },
    { label: 'LinkedIn', color: '#0A66C2', short: 'IN' },
    { label: 'GitHub', color: '#e6edf3', short: 'GH' },
    { label: 'Credly', color: '#FF6B35', short: 'CR' },
  ].map((s, i) => (
    <div key={i} style={{
      display: 'flex', alignItems: 'center', gap: '10px',
      background: '#0a0a0f', border: `1px solid ${s.color}44`,
      borderRadius: '8px', padding: '10px 24px', minWidth: '130px',
    }}>
      <div style={{
        width: '26px', height: '26px', borderRadius: '6px',
        background: s.color + '22', display: 'flex',
        alignItems: 'center', justifyContent: 'center',
        fontSize: '10px', fontWeight: '700', color: s.color,
      }}>{s.short}</div>
      <div style={{ fontSize: '12px', fontWeight: '600', color: s.color }}>{s.label}</div>
    </div>
  ))}
</div>
```
<div align="center">
  <a href="https://easwar-profile.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Website-00d4ff?style=for-the-badge&logo=vercel&logoColor=black" alt="Website" />
  </a>
  <a href="https://www.linkedin.com/in/easwaramurthy-p-8b561a294" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://www.credly.com/users/easwaramurthy-p" target="_blank">
    <img src="https://img.shields.io/badge/Credly-FF6B35?style=for-the-badge&logo=credly&logoColor=white" alt="Credly" />
  </a>
</div>

<br />

<div align="center">

![](https://komarev.com/ghpvc/?username=Easwarp45&label=Profile+Views&color=00d4ff&style=flat)

</div>
