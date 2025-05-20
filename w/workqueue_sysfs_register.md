# Function: <code>workqueue_sysfs_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109d460)
Location: kernel/workqueue.c:5107
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff8109d460-ffffffff8109d5b9: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0ac0)
Location: kernel/workqueue.c:5195
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810a0ac0-ffffffff810a0c09: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a5b90)
Location: kernel/workqueue.c:5225
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810a5b90-ffffffff810a5cd9: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a2c00)
Location: kernel/workqueue.c:5268
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810a2c00-ffffffff810a2d36: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a9530)
Location: kernel/workqueue.c:5299
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810a9530-ffffffff810a9666: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810afc60)
Location: kernel/workqueue.c:5416
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810afc60-ffffffff810afd96: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8dd0)
Location: kernel/workqueue.c:5439
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810b8dd0-ffffffff810b8f06: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:5586
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810bf578-ffffffff810bf590: workqueue_sysfs_register.cold (STB_LOCAL)
ffffffff810be8d0-ffffffff810be9f7: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4e80)
Location: kernel/workqueue.c:5620
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810c4e80-ffffffff810c4fac: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810cc8a0)
Location: kernel/workqueue.c:5643
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810cc8a0-ffffffff810cc9cc: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7a20)
Location: kernel/workqueue.c:5664
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810c7a20-ffffffff810c7b4c: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c94b0)
Location: kernel/workqueue.c:5671
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810c94b0-ffffffff810c95da: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810dc1b0)
Location: kernel/workqueue.c:5731
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810dc1b0-ffffffff810dc2da: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f5900)
Location: kernel/workqueue.c:5716
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810f5900-ffffffff810f5a39: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81117e30)
Location: kernel/workqueue.c:5714
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff81117e30-ffffffff81117f69: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81125050)
Location: kernel/workqueue.c:6113
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff81125050-ffffffff81125189: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112f820)
Location: kernel/workqueue.c:6300
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff8112f820-ffffffff8112f988: workqueue_sysfs_register (STB_GLOBAL)
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
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010123348)
Location: kernel/workqueue.c:5620
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffff800010123348-ffff8000101234a4: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0376c44)
Location: kernel/workqueue.c:5620
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
c0376c44-c0376da0: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016d270)
Location: kernel/workqueue.c:5620
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
c00000000016d270-c00000000016d454: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000dbb18)
Location: kernel/workqueue.c:5620
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffe0000dbb18-ffffffe0000dbc44: workqueue_sysfs_register (STB_GLOBAL)
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
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bf1f0)
Location: kernel/workqueue.c:5620
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810bf1f0-ffffffff810bf31c: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ada10)
Location: kernel/workqueue.c:5620
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810ada10-ffffffff810adb3c: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810be750)
Location: kernel/workqueue.c:5620
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810be750-ffffffff810be87c: workqueue_sysfs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int workqueue_sysfs_register(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6ac0)
Location: kernel/workqueue.c:5620
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810c6ac0-ffffffff810c6bec: workqueue_sysfs_register (STB_GLOBAL)
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
