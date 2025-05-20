# Function: <code>sched_setattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa1b0)
Location: kernel/sched/core.c:4060
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
**Symbols:**

```
ffffffff810aa1b0-ffffffff810aa1ca: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b047e)
Location: kernel/sched/core.c:4310
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
**Symbols:**

```
ffffffff810ace30-ffffffff810ace4a: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b660e)
Location: kernel/sched/core.c:4347
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
**Symbols:**

```
ffffffff810b2ec0-ffffffff810b2eda: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b288e)
Location: kernel/sched/core.c:4247
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
**Symbols:**

```
ffffffff810aede0-ffffffff810aedfa: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9c8e)
Location: kernel/sched/core.c:4291
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
**Symbols:**

```
ffffffff810b6020-ffffffff810b603a: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bddaa)
Location: kernel/sched/core.c:4421
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810bdd20-ffffffff810bdd3a: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6f5a)
Location: kernel/sched/core.c:4406
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810c6ed0-ffffffff810c6eea: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cd4d4)
Location: kernel/sched/core.c:4843
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810cd420-ffffffff810cd43a: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6f04)
Location: kernel/sched/core.c:5058
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810d6e50-ffffffff810d6e6a: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e141c)
Location: kernel/sched/core.c:5291
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810e1350-ffffffff810e136a: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de731)
Location: kernel/sched/core.c:6067
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810e3060-ffffffff810e307a: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0328)
Location: kernel/sched/core.c:6368
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810e5200-ffffffff810e521a: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f5577)
Location: kernel/sched/core.c:7531
Inline: True
Inline callers:
  - kernel/sched/core.c:__do_sys_sched_setattr
```
**Symbols:**

```
ffffffff810fc1e0-ffffffff810fc1fa: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81111fd9)
Location: kernel/sched/core.c:7639
Inline: True
Inline callers:
  - kernel/sched/core.c:__do_sys_sched_setattr
```
**Symbols:**

```
ffffffff81118750-ffffffff81118776: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81138fc9)
Location: kernel/sched/core.c:7781
Inline: True
Inline callers:
  - kernel/sched/core.c:__do_sys_sched_setattr
```
**Symbols:**

```
ffffffff8113fe30-ffffffff8113fe56: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81148239)
Location: kernel/sched/core.c:7890
Inline: True
Inline callers:
  - kernel/sched/core.c:__do_sys_sched_setattr
```
**Symbols:**

```
ffffffff8114c300-ffffffff8114c326: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81153a34)
Location: kernel/sched/core.c:7951
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff81157fc0-ffffffff81157fe6: sched_setattr (STB_GLOBAL)
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
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff8000101378bc)
Location: kernel/sched/core.c:5058
Inline: True
Inline callers:
  - kernel/sched/core.c:__arm64_sys_sched_setattr
```
**Symbols:**

```
ffff800010137680-ffff8000101376bc: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038c468)
Location: kernel/sched/core.c:5058
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
```
**Symbols:**

```
c0386564-c0386588: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000182fa4)
Location: kernel/sched/core.c:5058
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
```
**Symbols:**

```
c000000000182cf0-c000000000182d0c: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ebab4)
Location: kernel/sched/core.c:5058
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
```
**Symbols:**

```
ffffffe0000e7d1a-ffffffe0000e7d50: sched_setattr (STB_GLOBAL)
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
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d14d4)
Location: kernel/sched/core.c:5058
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810d1420-ffffffff810d143a: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bf844)
Location: kernel/sched/core.c:5058
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810bf790-ffffffff810bf7aa: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf594)
Location: kernel/sched/core.c:5058
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810cf4e0-ffffffff810cf4fa: sched_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8bb9)
Location: kernel/sched/core.c:5058
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810d8b00-ffffffff810d8b1a: sched_setattr (STB_GLOBAL)
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
