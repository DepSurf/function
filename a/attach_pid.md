# Function: <code>attach_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109e5e0)
Location: kernel/pid.c:389
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8109e5e0-ffffffff8109e630: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1d06)
Location: kernel/pid.c:389
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
**Symbols:**

```
ffffffff810a1c80-ffffffff810a1ccc: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6dc6)
Location: kernel/pid.c:389
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
**Symbols:**

```
ffffffff810a6d40-ffffffff810a6d8c: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a3d06)
Location: kernel/pid.c:390
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
**Symbols:**

```
ffffffff810a3c80-ffffffff810a3ccc: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aa2f6)
Location: kernel/pid.c:259
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
**Symbols:**

```
ffffffff810aa270-ffffffff810aa2bc: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0f06)
Location: kernel/pid.c:271
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
**Symbols:**

```
ffffffff810b0e80-ffffffff810b0ecc: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ba026)
Location: kernel/pid.c:280
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
```
**Symbols:**

```
ffffffff810b9f80-ffffffff810b9fe5: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bff36)
Location: kernel/pid.c:283
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810bfe90-ffffffff810bfef4: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c6306)
Location: kernel/pid.c:283
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810c6260-ffffffff810c62c5: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ce178)
Location: kernel/pid.c:330
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810ce0e0-ffffffff810ce138: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8c48)
Location: kernel/pid.c:331
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810c8bb0-ffffffff810c8c0c: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ca6e8)
Location: kernel/pid.c:331
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810ca650-ffffffff810ca6a8: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dd58e)
Location: kernel/pid.c:331
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810dd4a0-ffffffff810dd54f: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f6e8e)
Location: kernel/pid.c:331
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810f6d90-ffffffff810f6e49: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff811195ac)
Location: kernel/pid.c:331
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81119490-ffffffff8111954e: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81126a8c)
Location: kernel/pid.c:334
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81126960-ffffffff81126a25: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8113106e)
Location: kernel/pid.c:334
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81130f50-ffffffff81131009: attach_pid (STB_GLOBAL)
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
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010124b5c)
Location: kernel/pid.c:283
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffff800010124a78-ffff800010124aec: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377b2c)
Location: kernel/pid.c:283
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c0377a90-c0377aec: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016e8e0)
Location: kernel/pid.c:283
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c00000000016e810-c00000000016e884: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dcafc)
Location: kernel/pid.c:283
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffe0000dca26-ffffffe0000dca9c: attach_pid (STB_GLOBAL)
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
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c0686)
Location: kernel/pid.c:283
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810c05e0-ffffffff810c0644: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aee86)
Location: kernel/pid.c:283
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810aede0-ffffffff810aee45: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfbd6)
Location: kernel/pid.c:283
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810bfb30-ffffffff810bfb95: attach_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void attach_pid(struct task_struct *task, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7fe6)
Location: kernel/pid.c:283
Inline: True
Inline callers:
  - kernel/pid.c:change_pid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810c7f40-ffffffff810c7fa4: attach_pid (STB_GLOBAL)
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
