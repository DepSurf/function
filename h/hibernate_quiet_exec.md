# Function: <code>hibernate_quiet_exec</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hibernate_quiet_exec(int (*func)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81111520)
Location: kernel/power/hibernate.c:804
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:activate_store
```
**Symbols:**

```
ffffffff81111520-ffffffff811116a1: hibernate_quiet_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hibernate_quiet_exec(int (*func)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81111f70)
Location: kernel/power/hibernate.c:804
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:activate_store
```
**Symbols:**

```
ffffffff81111f70-ffffffff811120f1: hibernate_quiet_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hibernate_quiet_exec(int (*func)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81131f90)
Location: kernel/power/hibernate.c:807
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:activate_store
```
**Symbols:**

```
ffffffff81131f90-ffffffff81132111: hibernate_quiet_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hibernate_quiet_exec(int (*func)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81153ca0)
Location: kernel/power/hibernate.c:810
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:activate_store
```
**Symbols:**

```
ffffffff81153ca0-ffffffff81153e1f: hibernate_quiet_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hibernate_quiet_exec(int (*func)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81183200)
Location: kernel/power/hibernate.c:815
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:activate_store
```
**Symbols:**

```
ffffffff81183200-ffffffff81183389: hibernate_quiet_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hibernate_quiet_exec(int (*func)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81194070)
Location: kernel/power/hibernate.c:816
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:activate_store
```
**Symbols:**

```
ffffffff81194070-ffffffff811941f9: hibernate_quiet_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hibernate_quiet_exec(int (*func)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811a2a60)
Location: kernel/power/hibernate.c:822
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:activate_store
```
**Symbols:**

```
ffffffff811a2a60-ffffffff811a2be9: hibernate_quiet_exec (STB_GLOBAL)
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
