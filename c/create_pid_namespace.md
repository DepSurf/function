# Function: <code>create_pid_namespace</code>

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
In kernel/pid_namespace.c (ffffffff8111f924)
Location: kernel/pid_namespace.c:82
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (ffffffff81127874)
Location: kernel/pid_namespace.c:82
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (ffffffff811314e3)
Location: kernel/pid_namespace.c:92
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (ffffffff81132aa8)
Location: kernel/pid_namespace.c:95
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (ffffffff8113f8ab)
Location: kernel/pid_namespace.c:96
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (ffffffff8114e20d)
Location: kernel/pid_namespace.c:77
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (ffffffff8115aeed)
Location: kernel/pid_namespace.c:77
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (ffffffff8116759d)
Location: kernel/pid_namespace.c:78
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (ffffffff8117345d)
Location: kernel/pid_namespace.c:78
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pid_namespace *create_pid_namespace(struct user_namespace *user_ns, struct pid_namespace *parent_pid_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81184ee0)
Location: kernel/pid_namespace.c:70
Inline: False
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff81184ee0-ffffffff8118518b: create_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pid_namespace *create_pid_namespace(struct user_namespace *user_ns, struct pid_namespace *parent_pid_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81182050)
Location: kernel/pid_namespace.c:70
Inline: False
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff81182050-ffffffff81182348: create_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pid_namespace *create_pid_namespace(struct user_namespace *user_ns, struct pid_namespace *parent_pid_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811831a0)
Location: kernel/pid_namespace.c:70
Inline: False
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff811831a0-ffffffff81183495: create_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pid_namespace *create_pid_namespace(struct user_namespace *user_ns, struct pid_namespace *parent_pid_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811ab250)
Location: kernel/pid_namespace.c:71
Inline: False
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff811ab250-ffffffff811ab573: create_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pid_namespace *create_pid_namespace(struct user_namespace *user_ns, struct pid_namespace *parent_pid_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811dc9a0)
Location: kernel/pid_namespace.c:71
Inline: False
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff811dc9a0-ffffffff811dcc9d: create_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pid_namespace *create_pid_namespace(struct user_namespace *user_ns, struct pid_namespace *parent_pid_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81222300)
Location: kernel/pid_namespace.c:71
Inline: False
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff81222300-ffffffff812225fd: create_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pid_namespace *create_pid_namespace(struct user_namespace *user_ns, struct pid_namespace *parent_pid_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81238930)
Location: kernel/pid_namespace.c:72
Inline: False
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff81238930-ffffffff81238c55: create_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pid_namespace *create_pid_namespace(struct user_namespace *user_ns, struct pid_namespace *parent_pid_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81252600)
Location: kernel/pid_namespace.c:73
Inline: False
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff81252600-ffffffff81252925: create_pid_namespace (STB_LOCAL)
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
In kernel/pid_namespace.c (ffff8000101e7790)
Location: kernel/pid_namespace.c:78
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (c0427b74)
Location: kernel/pid_namespace.c:78
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (c000000000258060)
Location: kernel/pid_namespace.c:78
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (ffffffe00015cc6a)
Location: kernel/pid_namespace.c:78
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (ffffffff8116ba7d)
Location: kernel/pid_namespace.c:78
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (ffffffff8115ec7d)
Location: kernel/pid_namespace.c:78
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (ffffffff8116984d)
Location: kernel/pid_namespace.c:78
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
In kernel/pid_namespace.c (ffffffff81176f6d)
Location: kernel/pid_namespace.c:78
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
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
