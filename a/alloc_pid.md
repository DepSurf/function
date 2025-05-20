# Function: <code>alloc_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109e110)
Location: kernel/pid.c:297
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8109e110-ffffffff8109e59d: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1780)
Location: kernel/pid.c:297
Inline: False
```
**Symbols:**

```
ffffffff810a1780-ffffffff810a1c3a: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6840)
Location: kernel/pid.c:297
Inline: False
```
**Symbols:**

```
ffffffff810a6840-ffffffff810a6cfa: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a37b0)
Location: kernel/pid.c:296
Inline: False
```
**Symbols:**

```
ffffffff810a37b0-ffffffff810a3c33: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a9fa0)
Location: kernel/pid.c:147
Inline: False
```
**Symbols:**

```
ffffffff810a9fa0-ffffffff810aa227: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0bc0)
Location: kernel/pid.c:159
Inline: False
```
**Symbols:**

```
ffffffff810b0bc0-ffffffff810b0e3a: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b9cc0)
Location: kernel/pid.c:159
Inline: False
```
**Symbols:**

```
ffffffff810b9cc0-ffffffff810b9f3f: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfbc0)
Location: kernel/pid.c:160
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810bfbc0-ffffffff810bfe4a: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c5f90)
Location: kernel/pid.c:160
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810c5f90-ffffffff810c621a: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns, pid_t *set_tid, size_t set_tid_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810cdd10)
Location: kernel/pid.c:158
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810cdd10-ffffffff810ce091: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns, pid_t *set_tid, size_t set_tid_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c87e0)
Location: kernel/pid.c:159
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810c87e0-ffffffff810c8b64: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns, pid_t *set_tid, size_t set_tid_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ca280)
Location: kernel/pid.c:159
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810ca280-ffffffff810ca610: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns, pid_t *set_tid, size_t set_tid_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dd0d0)
Location: kernel/pid.c:159
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810dd0d0-ffffffff810dd460: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns, pid_t *set_tid, size_t set_tid_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f69b0)
Location: kernel/pid.c:159
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810f69b0-ffffffff810f6d4c: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns, pid_t *set_tid, size_t set_tid_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81119090)
Location: kernel/pid.c:159
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81119090-ffffffff8111942c: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns, pid_t *set_tid, size_t set_tid_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81126560)
Location: kernel/pid.c:162
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81126560-ffffffff811268fc: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns, pid_t *set_tid, size_t set_tid_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81130b50)
Location: kernel/pid.c:162
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81130b50-ffffffff81130eec: alloc_pid (STB_GLOBAL)
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
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010124620)
Location: kernel/pid.c:160
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffff800010124620-ffff8000101249d8: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377774)
Location: kernel/pid.c:160
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c0377774-c0377a3c: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016e2d0)
Location: kernel/pid.c:160
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c00000000016e2d0-c00000000016e770: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dc65c)
Location: kernel/pid.c:160
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffe0000dc65c-ffffffe0000dc9a6: alloc_pid (STB_GLOBAL)
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
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c0310)
Location: kernel/pid.c:160
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810c0310-ffffffff810c059a: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aeb20)
Location: kernel/pid.c:160
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810aeb20-ffffffff810aed92: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf860)
Location: kernel/pid.c:160
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810bf860-ffffffff810bfaea: alloc_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pid *alloc_pid(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7c70)
Location: kernel/pid.c:160
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810c7c70-ffffffff810c7f0e: alloc_pid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pid_t *set_tid</code>
</li>
<li>
<b>Param added. </b>
<code>size_t set_tid_size</code>
</li>
</ul>
</details>
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
