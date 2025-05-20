# Function: <code>__kthread_cancel_work_sync</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a92c0)
Location: kernel/kthread.c:1052
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810a92c0-ffffffff810a93aa: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a5fe0)
Location: kernel/kthread.c:1057
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810a5fe0-ffffffff810a60ab: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ac4f0)
Location: kernel/kthread.c:1062
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810ac4f0-ffffffff810ac5bb: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3020)
Location: kernel/kthread.c:1080
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810b3020-ffffffff810b30eb: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc0b0)
Location: kernel/kthread.c:1082
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810bc0b0-ffffffff810bc17b: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c22a0)
Location: kernel/kthread.c:1092
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810c22a0-ffffffff810c2369: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8800)
Location: kernel/kthread.c:1092
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810c8800-ffffffff810c88c9: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d1210)
Location: kernel/kthread.c:1128
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810d1210-ffffffff810d12d9: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cbce0)
Location: kernel/kthread.c:1182
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810cbce0-ffffffff810cbda9: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd610)
Location: kernel/kthread.c:1237
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810cd610-ffffffff810cd6fa: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0800)
Location: kernel/kthread.c:1237
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810e0800-ffffffff810e08ea: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fa5d0)
Location: kernel/kthread.c:1297
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810fa5d0-ffffffff810fa6c2: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111d3c0)
Location: kernel/kthread.c:1297
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff8111d3c0-ffffffff8111d4b2: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112a4e0)
Location: kernel/kthread.c:1298
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff8112a4e0-ffffffff8112a5d2: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81134b70)
Location: kernel/kthread.c:1315
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff81134b70-ffffffff81134c62: __kthread_cancel_work_sync (STB_LOCAL)
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
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128bb0)
Location: kernel/kthread.c:1092
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffff800010128bb0-ffff800010128d90: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037a558)
Location: kernel/kthread.c:1092
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
c037a558-c037a67c: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000172240)
Location: kernel/kthread.c:1092
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
c000000000172240-c000000000172394: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000dfc18)
Location: kernel/kthread.c:1092
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffe0000dfc18-ffffffe0000dfcce: __kthread_cancel_work_sync (STB_LOCAL)
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
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2b80)
Location: kernel/kthread.c:1092
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810c2b80-ffffffff810c2c49: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b13c0)
Location: kernel/kthread.c:1092
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810b13c0-ffffffff810b1489: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c20d0)
Location: kernel/kthread.c:1092
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810c20d0-ffffffff810c2199: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work *work, bool is_dwork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ca690)
Location: kernel/kthread.c:1092
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_cancel_delayed_work_sync
  - kernel/kthread.c:kthread_cancel_work_sync
```
**Symbols:**

```
ffffffff810ca690-ffffffff810ca759: __kthread_cancel_work_sync (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
