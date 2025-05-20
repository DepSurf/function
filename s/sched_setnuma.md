# Function: <code>sched_setnuma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aea40)
Location: kernel/sched/core.c:5145
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810aea40-ffffffff810aebc4: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b1410)
Location: kernel/sched/core.c:5403
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810b1410-ffffffff810b1525: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b7680)
Location: kernel/sched/core.c:5437
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810b7680-ffffffff810b77db: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3860)
Location: kernel/sched/core.c:5320
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810b3860-ffffffff810b399f: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810baad0)
Location: kernel/sched/core.c:5399
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810baad0-ffffffff810bac37: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1f40)
Location: kernel/sched/core.c:5524
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810c1f40-ffffffff810c208f: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cb270)
Location: kernel/sched/core.c:5507
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810cb270-ffffffff810cb3ac: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2f10)
Location: kernel/sched/core.c:5959
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810d2f10-ffffffff810d3418: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dd3a0)
Location: kernel/sched/core.c:6152
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810dd3a0-ffffffff810dd98e: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e5f60)
Location: kernel/sched/core.c:6386
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810e5f60-ffffffff810e614c: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3ca0)
Location: kernel/sched/core.c:7200
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810e3ca0-ffffffff810e3eac: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e5c70)
Location: kernel/sched/core.c:7564
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810e5c70-ffffffff810e5e7c: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fcd70)
Location: kernel/sched/core.c:8761
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810fcd70-ffffffff810fcfd4: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81119720)
Location: kernel/sched/core.c:9049
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff81119720-ffffffff81119988: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81141020)
Location: kernel/sched/core.c:9239
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff81141020-ffffffff81141296: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114cc90)
Location: kernel/sched/core.c:9383
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff8114cc90-ffffffff8114cf1e: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81158950)
Location: kernel/sched/core.c:9370
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff81158950-ffffffff81158bde: sched_setnuma (STB_GLOBAL)
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
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013cf00)
Location: kernel/sched/core.c:6152
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffff80001013cf00-ffff80001013d060: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018b710)
Location: kernel/sched/core.c:6152
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
c00000000018b710-c00000000018bde8: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7590)
Location: kernel/sched/core.c:6152
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810d7590-ffffffff810d7b80: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c5eb0)
Location: kernel/sched/core.c:6152
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810c5eb0-ffffffff810c649e: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d41f0)
Location: kernel/sched/core.c:6152
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810d41f0-ffffffff810d436a: sched_setnuma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sched_setnuma(struct task_struct *p, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df190)
Location: kernel/sched/core.c:6152
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810df190-ffffffff810df77e: sched_setnuma (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
