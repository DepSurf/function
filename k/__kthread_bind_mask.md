# Function: <code>__kthread_bind_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a0690)
Location: kernel/kthread.c:343
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_bind
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810a0690-ffffffff810a0705: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a3d80)
Location: kernel/kthread.c:343
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_bind
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810a3d80-ffffffff810a3df5: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a93f0)
Location: kernel/kthread.c:373
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810a93f0-ffffffff810a9465: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a60f0)
Location: kernel/kthread.c:377
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810a60f0-ffffffff810a6156: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ac690)
Location: kernel/kthread.c:384
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810ac690-ffffffff810ac6f6: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b2d30)
Location: kernel/kthread.c:398
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810b2d30-ffffffff810b2d96: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc1c0)
Location: kernel/kthread.c:398
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810bc1c0-ffffffff810bc226: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (ffffffff810c32ab)
Location: kernel/kthread.c:407
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810c23b0-ffffffff810c240f: __kthread_bind_mask (STB_LOCAL)
ffffffff810c32ab-ffffffff810c32be: __kthread_bind_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8ae0)
Location: kernel/kthread.c:407
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810c8ae0-ffffffff810c8b46: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0090)
Location: kernel/kthread.c:443
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810d0090-ffffffff810d00f6: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810caa80)
Location: kernel/kthread.c:445
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810caa80-ffffffff810caae6: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cc520)
Location: kernel/kthread.c:472
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810cc520-ffffffff810cc586: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0ddb)
Location: kernel/kthread.c:472
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/kthread.c:__kthread_bind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fb23b)
Location: kernel/kthread.c:531
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/kthread.c:__kthread_bind
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111e13b)
Location: kernel/kthread.c:531
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/kthread.c:__kthread_bind
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112b39b)
Location: kernel/kthread.c:532
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/kthread.c:__kthread_bind
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
In kernel/kthread.c (ffffffff81135aeb)
Location: kernel/kthread.c:531
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/kthread.c:__kthread_bind
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff8000101280b0)
Location: kernel/kthread.c:407
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffff8000101280b0-ffff800010128198: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037a8fc)
Location: kernel/kthread.c:407
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
c037a8fc-c037a980: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0000000001726f0)
Location: kernel/kthread.c:407
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
c0000000001726f0-c0000000001727b4: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df202)
Location: kernel/kthread.c:407
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffe0000df202-ffffffe0000df284: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2e60)
Location: kernel/kthread.c:407
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810c2e60-ffffffff810c2ec6: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b16a0)
Location: kernel/kthread.c:407
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810b16a0-ffffffff810b1706: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c23b0)
Location: kernel/kthread.c:407
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810c23b0-ffffffff810c2416: __kthread_bind_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __kthread_bind_mask(struct task_struct *p, const struct cpumask *mask, long int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ca970)
Location: kernel/kthread.c:407
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_bind_mask
```
**Symbols:**

```
ffffffff810ca970-ffffffff810ca9d6: __kthread_bind_mask (STB_LOCAL)
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
