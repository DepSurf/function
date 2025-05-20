# Function: <code>detach_tasks</code>

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
In kernel/sched/fair.c (ffffffff810bd4d8)
Location: kernel/sched/fair.c:5783
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810c0c3e)
Location: kernel/sched/fair.c:6244
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810c6c27)
Location: kernel/sched/fair.c:6785
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810c0812)
Location: kernel/sched/fair.c:6748
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810c7f24)
Location: kernel/sched/fair.c:7195
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810cff55)
Location: kernel/sched/fair.c:7482
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810d977b)
Location: kernel/sched/fair.c:7488
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810e09f3)
Location: kernel/sched/fair.c:7387
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810eb083)
Location: kernel/sched/fair.c:7349
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int detach_tasks(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f1970)
Location: kernel/sched/fair.c:7606
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff810f1970-ffffffff810f1c6b: detach_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int detach_tasks(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eeea0)
Location: kernel/sched/fair.c:7682
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff810eeea0-ffffffff810ef18e: detach_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int detach_tasks(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f2b60)
Location: kernel/sched/fair.c:7798
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff810f2b60-ffffffff810f2e4c: detach_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int detach_tasks(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110a2f0)
Location: kernel/sched/fair.c:7936
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff8110a2f0-ffffffff8110a62d: detach_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int detach_tasks(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81125c90)
Location: kernel/sched/fair.c:7910
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff81125c90-ffffffff81125fe3: detach_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int detach_tasks(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8114ef30)
Location: kernel/sched/fair.c:8360
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff8114ef30-ffffffff8114f3a7: detach_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int detach_tasks(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81160570)
Location: kernel/sched/fair.c:8718
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff81160570-ffffffff81160969: detach_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int detach_tasks(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116a9a0)
Location: kernel/sched/fair.c:9041
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff8116a9a0-ffffffff8116ad1a: detach_tasks (STB_LOCAL)
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
In kernel/sched/fair.c (ffff80001014b194)
Location: kernel/sched/fair.c:7349
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (c0398ef4)
Location: kernel/sched/fair.c:7349
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (c00000000019d72c)
Location: kernel/sched/fair.c:7349
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffe0000f4a92)
Location: kernel/sched/fair.c:7349
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810e51e3)
Location: kernel/sched/fair.c:7349
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810d4392)
Location: kernel/sched/fair.c:7349
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810e15b3)
Location: kernel/sched/fair.c:7349
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810ed150)
Location: kernel/sched/fair.c:7349
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
