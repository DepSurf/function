# Function: <code>security_sem_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_sem_alloc(struct sem_array *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133ee30)
Location: security/security.c:1099
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff8133ee30-ffffffff8133ee73: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_sem_alloc(struct sem_array *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374450)
Location: security/security.c:1123
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff81374450-ffffffff81374493: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_sem_alloc(struct sem_array *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138ad80)
Location: security/security.c:1144
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff8138ad80-ffffffff8138adc3: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_sem_alloc(struct sem_array *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a0450)
Location: security/security.c:1884
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff813a0450-ffffffff813a04b9: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_sem_alloc(struct sem_array *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c6200)
Location: security/security.c:1855
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff813c6200-ffffffff813c629c: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5e30)
Location: security/security.c:1248
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff813f5e30-ffffffff813f5e6a: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814115d0)
Location: security/security.c:1883
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff814115d0-ffffffff81411651: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ee50)
Location: security/security.c:1902
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff8143ee50-ffffffff8143eed3: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81458810)
Location: security/security.c:1941
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff81458810-ffffffff81458891: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab6d0)
Location: security/security.c:2143
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff814ab6d0-ffffffff814ab77e: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8cd0)
Location: security/security.c:2160
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff814c8cd0-ffffffff814c8d7e: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf310)
Location: security/security.c:2223
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff814cf310-ffffffff814cf3be: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527fd0)
Location: security/security.c:2231
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff81527fd0-ffffffff8152807e: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bd060)
Location: security/security.c:2242
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff815bd060-ffffffff815bd128: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816693b0)
Location: security/security.c:2318
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff816693b0-ffffffff81669478: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a19b0)
Location: security/security.c:3906
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff816a19b0-ffffffff816a1a78: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816de230)
Location: security/security.c:3935
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff816de230-ffffffff816de2f8: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544720)
Location: security/security.c:1941
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffff800010544720-ffff8000105447b4: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa60c)
Location: security/security.c:1941
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
c06fa60c-c06fa6a0: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000699660)
Location: security/security.c:1941
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
c000000000699660-c000000000699758: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a0818)
Location: security/security.c:1941
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffe0003a0818-ffffffe0003a0896: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450df0)
Location: security/security.c:1941
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff81450df0-ffffffff81450e71: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441840)
Location: security/security.c:1941
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff81441840-ffffffff814418c1: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ce90)
Location: security/security.c:1941
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff8144ce90-ffffffff8144cf11: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_sem_alloc(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81464260)
Location: security/security.c:1941
Inline: False
Direct callers:
  - ipc/sem.c:newary
```
**Symbols:**

```
ffffffff81464260-ffffffff814642e1: security_sem_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sem_array *sma</code> ➡️ <code>struct kern_ipc_perm *sma</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
