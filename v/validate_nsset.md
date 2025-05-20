# Function: <code>validate_nsset</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int validate_nsset(struct nsset *nsset, struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d5f70)
Location: kernel/nsproxy.c:357
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff810d5f70-ffffffff810d6298: validate_nsset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int validate_nsset(struct nsset *nsset, struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d0aa0)
Location: kernel/nsproxy.c:356
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff810d0aa0-ffffffff810d0e3d: validate_nsset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int validate_nsset(struct nsset *nsset, struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d2680)
Location: kernel/nsproxy.c:356
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff810d2680-ffffffff810d2a19: validate_nsset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int validate_nsset(struct nsset *nsset, struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810e57c0)
Location: kernel/nsproxy.c:356
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff810e57c0-ffffffff810e5b59: validate_nsset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int validate_nsset(struct nsset *nsset, struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ff5d0)
Location: kernel/nsproxy.c:356
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff810ff5d0-ffffffff810ff99b: validate_nsset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int validate_nsset(struct nsset *nsset, struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff81124300)
Location: kernel/nsproxy.c:375
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff81124300-ffffffff811246cb: validate_nsset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int validate_nsset(struct nsset *nsset, struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff81131600)
Location: kernel/nsproxy.c:375
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff81131600-ffffffff811319cb: validate_nsset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int validate_nsset(struct nsset *nsset, struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff8113c390)
Location: kernel/nsproxy.c:375
Inline: False
Direct callers:
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff8113c390-ffffffff8113c7d1: validate_nsset (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
