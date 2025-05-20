# Function: <code>transfer_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109e6b0)
Location: kernel/pid.c:428
Inline: False
```
**Symbols:**

```
ffffffff8109e6b0-ffffffff8109e72f: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1d50)
Location: kernel/pid.c:428
Inline: False
```
**Symbols:**

```
ffffffff810a1d50-ffffffff810a1dcf: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6e10)
Location: kernel/pid.c:428
Inline: False
```
**Symbols:**

```
ffffffff810a6e10-ffffffff810a6e8f: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a3d50)
Location: kernel/pid.c:429
Inline: False
```
**Symbols:**

```
ffffffff810a3d50-ffffffff810a3dcf: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aa340)
Location: kernel/pid.c:298
Inline: False
```
**Symbols:**

```
ffffffff810aa340-ffffffff810aa3bf: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0f50)
Location: kernel/pid.c:310
Inline: False
```
**Symbols:**

```
ffffffff810b0f50-ffffffff810b0fc1: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ba090)
Location: kernel/pid.c:318
Inline: False
```
**Symbols:**

```
ffffffff810ba090-ffffffff810ba107: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bffa0)
Location: kernel/pid.c:321
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810bffa0-ffffffff810c0015: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c6370)
Location: kernel/pid.c:321
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810c6370-ffffffff810c63e7: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ce240)
Location: kernel/pid.c:387
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810ce240-ffffffff810ce2bc: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8d10)
Location: kernel/pid.c:388
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810c8d10-ffffffff810c8d8e: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ca7b0)
Location: kernel/pid.c:388
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810ca7b0-ffffffff810ca82c: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dd6a0)
Location: kernel/pid.c:388
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810dd6a0-ffffffff810dd77d: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f6fc0)
Location: kernel/pid.c:388
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810f6fc0-ffffffff810f70b3: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81119700)
Location: kernel/pid.c:388
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff81119700-ffffffff811197f5: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81126be0)
Location: kernel/pid.c:391
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff81126be0-ffffffff81126cd6: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff811311c0)
Location: kernel/pid.c:391
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff811311c0-ffffffff811312b3: transfer_pid (STB_GLOBAL)
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
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010124bb8)
Location: kernel/pid.c:321
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffff800010124bb8-ffff800010124c3c: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377b74)
Location: kernel/pid.c:321
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
c0377b74-c0377be0: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016e970)
Location: kernel/pid.c:321
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
c00000000016e970-c00000000016e9e4: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dcb5a)
Location: kernel/pid.c:321
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffe0000dcb5a-ffffffe0000dcbce: transfer_pid (STB_GLOBAL)
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
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c06f0)
Location: kernel/pid.c:321
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810c06f0-ffffffff810c0765: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aeef0)
Location: kernel/pid.c:321
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810aeef0-ffffffff810aef67: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfc40)
Location: kernel/pid.c:321
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810bfc40-ffffffff810bfcb7: transfer_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void transfer_pid(struct task_struct *old, struct task_struct *new, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8050)
Location: kernel/pid.c:321
Inline: False
Direct callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810c8050-ffffffff810c80c5: transfer_pid (STB_GLOBAL)
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
