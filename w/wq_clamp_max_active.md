# Function: <code>wq_clamp_max_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810976c0)
Location: kernel/workqueue.c:3785
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810976c0-ffffffff8109774d: wq_clamp_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109ada0)
Location: kernel/workqueue.c:3883
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff8109ada0-ffffffff8109ae2d: wq_clamp_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a34a0)
Location: kernel/workqueue.c:3911
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810a34a0-ffffffff810a352e: wq_clamp_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a07b0)
Location: kernel/workqueue.c:3920
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810a07b0-ffffffff810a083e: wq_clamp_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a7040)
Location: kernel/workqueue.c:3931
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810a7040-ffffffff810a70ce: wq_clamp_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ad320)
Location: kernel/workqueue.c:4004
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810ad320-ffffffff810ad3a8: wq_clamp_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b6cf0)
Location: kernel/workqueue.c:4027
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810b6cf0-ffffffff810b6d78: wq_clamp_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4167
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810bd160-ffffffff810bd1d5: wq_clamp_max_active (STB_LOCAL)
ffffffff810bf085-ffffffff810bf0a3: wq_clamp_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4185
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810c2de0-ffffffff810c2e55: wq_clamp_max_active (STB_LOCAL)
ffffffff810c5505-ffffffff810c5523: wq_clamp_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4194
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810c6e80-ffffffff810c6ee8: wq_clamp_max_active (STB_LOCAL)
ffffffff810cd031-ffffffff810cd04f: wq_clamp_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4207
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810c1f90-ffffffff810c1ff8: wq_clamp_max_active (STB_LOCAL)
ffffffff81bdbe86-ffffffff81bdbea4: wq_clamp_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4214
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810c3670-ffffffff810c36d4: wq_clamp_max_active (STB_LOCAL)
ffffffff81bcdf6c-ffffffff81bcdf8a: wq_clamp_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4253
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810d6210-ffffffff810d6274: wq_clamp_max_active (STB_LOCAL)
ffffffff81ca5019-ffffffff81ca5037: wq_clamp_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4236
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810efaf0-ffffffff810efb63: wq_clamp_max_active (STB_LOCAL)
ffffffff81e548f7-ffffffff81e54915: wq_clamp_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81111430)
Location: kernel/workqueue.c:4245
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff81111430-ffffffff811114b9: wq_clamp_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111d810)
Location: kernel/workqueue.c:4573
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff8111d810-ffffffff8111d899: wq_clamp_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811288d3)
Location: kernel/workqueue.c:4615
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
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
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011bbe0)
Location: kernel/workqueue.c:4185
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffff80001011bbe0-ffff80001011bc7c: wq_clamp_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c03716bc)
Location: kernel/workqueue.c:4185
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
c03716bc-c0371754: wq_clamp_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000163b90)
Location: kernel/workqueue.c:4185
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
c000000000163b90-c000000000163c9c: wq_clamp_max_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d70aa)
Location: kernel/workqueue.c:4185
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffe0000d70aa-ffffffe0000d7142: wq_clamp_max_active (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4185
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810bd150-ffffffff810bd1c5: wq_clamp_max_active (STB_LOCAL)
ffffffff810bf875-ffffffff810bf893: wq_clamp_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4185
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810ab980-ffffffff810ab9f5: wq_clamp_max_active (STB_LOCAL)
ffffffff810ae095-ffffffff810ae0b3: wq_clamp_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4185
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810bc6b0-ffffffff810bc725: wq_clamp_max_active (STB_LOCAL)
ffffffff810bedd5-ffffffff810bedf3: wq_clamp_max_active.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int wq_clamp_max_active(int max_active, unsigned int flags, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4185
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_set_max_active
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810c4a40-ffffffff810c4ab5: wq_clamp_max_active (STB_LOCAL)
ffffffff810c7140-ffffffff810c715e: wq_clamp_max_active.cold (STB_LOCAL)
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
