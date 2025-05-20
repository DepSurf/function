# Function: <code>__kthread_bind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a0715)
Location: kernel/kthread.c:359
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_bind
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a3e05)
Location: kernel/kthread.c:359
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_bind
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a9756)
Location: kernel/kthread.c:389
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6407)
Location: kernel/kthread.c:393
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810aca37)
Location: kernel/kthread.c:400
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3487)
Location: kernel/kthread.c:414
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc5c7)
Location: kernel/kthread.c:414
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c24de)
Location: kernel/kthread.c:423
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8c1e)
Location: kernel/kthread.c:423
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0eca)
Location: kernel/kthread.c:459
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb97a)
Location: kernel/kthread.c:461
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd1fa)
Location: kernel/kthread.c:488
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __kthread_bind(struct task_struct *p, unsigned int cpu, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810df800)
Location: kernel/kthread.c:488
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
**Symbols:**

```
ffffffff810df800-ffffffff810df8a6: __kthread_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __kthread_bind(struct task_struct *p, unsigned int cpu, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810f9a60)
Location: kernel/kthread.c:547
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
**Symbols:**

```
ffffffff810f9a60-ffffffff810f9b33: __kthread_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __kthread_bind(struct task_struct *p, unsigned int cpu, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111c7d0)
Location: kernel/kthread.c:547
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
**Symbols:**

```
ffffffff8111c7d0-ffffffff8111c8a3: __kthread_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __kthread_bind(struct task_struct *p, unsigned int cpu, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81129960)
Location: kernel/kthread.c:548
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
**Symbols:**

```
ffffffff81129960-ffffffff81129a33: __kthread_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __kthread_bind(struct task_struct *p, unsigned int cpu, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81133fa0)
Location: kernel/kthread.c:547
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
**Symbols:**

```
ffffffff81133fa0-ffffffff81134073: __kthread_bind (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128298)
Location: kernel/kthread.c:423
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037b200)
Location: kernel/kthread.c:423
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0000000001728c4)
Location: kernel/kthread.c:423
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df852)
Location: kernel/kthread.c:423
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2f9e)
Location: kernel/kthread.c:423
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b17de)
Location: kernel/kthread.c:423
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c24ee)
Location: kernel/kthread.c:423
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810caaae)
Location: kernel/kthread.c:423
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
