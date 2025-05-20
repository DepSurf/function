# Function: <code>hibernate_acquire</code>

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
bool hibernate_acquire();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81114cb0)
Location: kernel/power/hibernate.c:72
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81114cb0-ffffffff81114ce4: hibernate_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool hibernate_acquire();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811114e0)
Location: kernel/power/hibernate.c:72
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff811114e0-ffffffff81111514: hibernate_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool hibernate_acquire();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81111f30)
Location: kernel/power/hibernate.c:72
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81111f30-ffffffff81111f64: hibernate_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool hibernate_acquire();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81131f50)
Location: kernel/power/hibernate.c:73
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81131f50-ffffffff81131f84: hibernate_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool hibernate_acquire();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81153c60)
Location: kernel/power/hibernate.c:72
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81153c60-ffffffff81153c9b: hibernate_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool hibernate_acquire();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811831b0)
Location: kernel/power/hibernate.c:72
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff811831b0-ffffffff811831eb: hibernate_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool hibernate_acquire();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81194020)
Location: kernel/power/hibernate.c:73
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81194020-ffffffff8119405b: hibernate_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool hibernate_acquire();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811a2a10)
Location: kernel/power/hibernate.c:73
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff811a2a10-ffffffff811a2a4b: hibernate_acquire (STB_GLOBAL)
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
