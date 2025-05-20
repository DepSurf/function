# Function: <code>kdb_send_sig</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a2d90)
Location: kernel/signal.c:3941
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810a2d90-ffffffff810a2e64: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab990)
Location: kernel/signal.c:4312
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810ab990-ffffffff810aba64: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0e80)
Location: kernel/signal.c:4582
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810b0e80-ffffffff810b0f45: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b75d0)
Location: kernel/signal.c:4590
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810b75d0-ffffffff810b7695: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bf520)
Location: kernel/signal.c:4608
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810bf520-ffffffff810bf5e5: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba720)
Location: kernel/signal.c:4645
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810ba720-ffffffff810ba7e5: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bc050)
Location: kernel/signal.c:4670
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810bc050-ffffffff810bc115: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cea40)
Location: kernel/signal.c:4754
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810cea40-ffffffff810ceb03: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e69f0)
Location: kernel/signal.c:4770
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810e69f0-ffffffff810e6b07: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811076b0)
Location: kernel/signal.c:4772
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff811076b0-ffffffff811077c7: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811139a0)
Location: kernel/signal.c:4818
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff811139a0-ffffffff81113ab7: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111d390)
Location: kernel/signal.c:4829
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff8111d390-ffffffff8111d4a7: kdb_send_sig (STB_GLOBAL)
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
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010113a58)
Location: kernel/signal.c:4590
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffff800010113a58-ffff800010113b70: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036aa0c)
Location: kernel/signal.c:4590
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
c036aa0c-c036ab04: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c00000000015b6c0)
Location: kernel/signal.c:4590
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
c00000000015b6c0-c00000000015b880: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1940)
Location: kernel/signal.c:4590
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810b1940-ffffffff810b1a05: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a0260)
Location: kernel/signal.c:4590
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810a0260-ffffffff810a0325: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0ea0)
Location: kernel/signal.c:4590
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810b0ea0-ffffffff810b0f65: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kdb_send_sig(struct task_struct *t, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9170)
Location: kernel/signal.c:4590
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810b9170-ffffffff810b923d: kdb_send_sig (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
