# Function: <code>__kthread_queue_delayed_work</code>

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
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a9f90)
Location: kernel/kthread.c:839
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810a9f90-ffffffff810aa06f: __kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6bc0)
Location: kernel/kthread.c:845
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810a6bc0-ffffffff810a6c4e: __kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ad330)
Location: kernel/kthread.c:851
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810ad330-ffffffff810ad3b8: __kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b40a0)
Location: kernel/kthread.c:869
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810b40a0-ffffffff810b4128: __kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bd1f0)
Location: kernel/kthread.c:871
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810bd1f0-ffffffff810bd278: __kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c30b0)
Location: kernel/kthread.c:881
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810c30b0-ffffffff810c3139: __kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8910)
Location: kernel/kthread.c:881
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810c8910-ffffffff810c8999: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0400)
Location: kernel/kthread.c:917
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810d0400-ffffffff810d0489: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cae20)
Location: kernel/kthread.c:971
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810cae20-ffffffff810caea9: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cc730)
Location: kernel/kthread.c:998
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810cc730-ffffffff810cc7b9: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810dfc30)
Location: kernel/kthread.c:998
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810dfc30-ffffffff810dfca7: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fa710)
Location: kernel/kthread.c:1058
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810fa710-ffffffff810fa79f: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111d530)
Location: kernel/kthread.c:1059
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff8111d530-ffffffff8111d5bf: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112a650)
Location: kernel/kthread.c:1060
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff8112a650-ffffffff8112a6df: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81134ce0)
Location: kernel/kthread.c:1077
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff81134ce0-ffffffff81134d6f: __kthread_queue_delayed_work (STB_LOCAL)
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
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010127388)
Location: kernel/kthread.c:881
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffff800010127388-ffff800010127438: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037a6bc)
Location: kernel/kthread.c:881
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
c037a6bc-c037a780: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0000000001723e0)
Location: kernel/kthread.c:881
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
c0000000001723e0-c0000000001724c8: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df062)
Location: kernel/kthread.c:881
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffe0000df062-ffffffe0000df0fe: __kthread_queue_delayed_work (STB_LOCAL)
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
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2c90)
Location: kernel/kthread.c:881
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810c2c90-ffffffff810c2d19: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b14d0)
Location: kernel/kthread.c:881
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810b14d0-ffffffff810b1559: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c21e0)
Location: kernel/kthread.c:881
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810c21e0-ffffffff810c2269: __kthread_queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ca7a0)
Location: kernel/kthread.c:881
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_queue_delayed_work
```
**Symbols:**

```
ffffffff810ca7a0-ffffffff810ca829: __kthread_queue_delayed_work (STB_LOCAL)
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
