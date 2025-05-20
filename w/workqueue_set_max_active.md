# Function: <code>workqueue_set_max_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81099a70)
Location: kernel/workqueue.c:3991
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff81099a70-ffffffff81099b00: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109d000)
Location: kernel/workqueue.c:4089
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff8109d000-ffffffff8109d090: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3530)
Location: kernel/workqueue.c:4119
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810a3530-ffffffff810a35c0: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0840)
Location: kernel/workqueue.c:4138
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810a0840-ffffffff810a08c6: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a70d0)
Location: kernel/workqueue.c:4149
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810a70d0-ffffffff810a715c: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ad3b0)
Location: kernel/workqueue.c:4232
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810ad3b0-ffffffff810ad43c: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b6d80)
Location: kernel/workqueue.c:4255
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810b6d80-ffffffff810b6e0c: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4398
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810bf0a3-ffffffff810bf0b6: workqueue_set_max_active.cold (STB_LOCAL)
ffffffff810bd1e0-ffffffff810bd268: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2e60)
Location: kernel/workqueue.c:4431
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810c2e60-ffffffff810c2eed: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7890)
Location: kernel/workqueue.c:4454
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810c7890-ffffffff810c791d: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2870)
Location: kernel/workqueue.c:4467
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810c2870-ffffffff810c28fd: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4570)
Location: kernel/workqueue.c:4474
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810c4570-ffffffff810c45fd: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d7190)
Location: kernel/workqueue.c:4513
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810d7190-ffffffff810d721d: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f0e30)
Location: kernel/workqueue.c:4496
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810f0e30-ffffffff810f0ed5: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81112aa0)
Location: kernel/workqueue.c:4505
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff81112aa0-ffffffff81112b45: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111f790)
Location: kernel/workqueue.c:4843
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff8111f790-ffffffff8111f835: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811288b0)
Location: kernel/workqueue.c:4868
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff811288b0-ffffffff81128988: workqueue_set_max_active (STB_GLOBAL)
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
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011dff0)
Location: kernel/workqueue.c:4431
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffff80001011dff0-ffff80001011e098: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c03719e0)
Location: kernel/workqueue.c:4431
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
c03719e0-c0371a80: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0000000001661f0)
Location: kernel/workqueue.c:4431
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
c0000000001661f0-c0000000001662d4: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d7142)
Location: kernel/workqueue.c:4431
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffe0000d7142-ffffffe0000d71e2: workqueue_set_max_active (STB_GLOBAL)
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
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd1d0)
Location: kernel/workqueue.c:4431
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810bd1d0-ffffffff810bd25d: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810aba00)
Location: kernel/workqueue.c:4431
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810aba00-ffffffff810aba8d: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bc730)
Location: kernel/workqueue.c:4431
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810bc730-ffffffff810bc7bd: workqueue_set_max_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void workqueue_set_max_active(struct workqueue_struct *wq, int max_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4ac0)
Location: kernel/workqueue.c:4431
Inline: False
Direct callers:
  - kernel/workqueue.c:max_active_store
```
**Symbols:**

```
ffffffff810c4ac0-ffffffff810c4b4d: workqueue_set_max_active (STB_GLOBAL)
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
