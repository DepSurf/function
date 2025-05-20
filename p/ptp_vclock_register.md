# Function: <code>ptp_vclock_register</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ptp_vclock *ptp_vclock_register(struct ptp_clock *pclock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff819db350)
Location: drivers/ptp/ptp_vclock.c:117
Inline: False
Direct callers:
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
```
**Symbols:**

```
ffffffff819db350-ffffffff819db4b2: ptp_vclock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ptp_vclock *ptp_vclock_register(struct ptp_clock *pclock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81b3ec80)
Location: drivers/ptp/ptp_vclock.c:185
Inline: False
Direct callers:
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
```
**Symbols:**

```
ffffffff81b3ec80-ffffffff81b3eea1: ptp_vclock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ptp_vclock *ptp_vclock_register(struct ptp_clock *pclock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81cd5020)
Location: drivers/ptp/ptp_vclock.c:185
Inline: False
Direct callers:
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
```
**Symbols:**

```
ffffffff81cd5020-ffffffff81cd524e: ptp_vclock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ptp_vclock *ptp_vclock_register(struct ptp_clock *pclock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81d3cca0)
Location: drivers/ptp/ptp_vclock.c:185
Inline: False
Direct callers:
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
```
**Symbols:**

```
ffffffff81d3cca0-ffffffff81d3ced1: ptp_vclock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ptp_vclock *ptp_vclock_register(struct ptp_clock *pclock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81df35e0)
Location: drivers/ptp/ptp_vclock.c:185
Inline: False
Direct callers:
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
```
**Symbols:**

```
ffffffff81df35e0-ffffffff81df3840: ptp_vclock_register (STB_GLOBAL)
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
