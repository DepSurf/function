# Function: <code>ptp_vclock_unregister</code>

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
void ptp_vclock_unregister(struct ptp_vclock *vclock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff819db4c0)
Location: drivers/ptp/ptp_vclock.c:146
Inline: False
Direct callers:
  - drivers/ptp/ptp_sysfs.c:unregister_vclock
```
**Symbols:**

```
ffffffff819db4c0-ffffffff819db4e8: ptp_vclock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ptp_vclock_unregister(struct ptp_vclock *vclock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81b3eeb0)
Location: drivers/ptp/ptp_vclock.c:224
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:unregister_vclock
  - drivers/ptp/ptp_sysfs.c:unregister_vclock
```
**Symbols:**

```
ffffffff81b3eeb0-ffffffff81b3ef28: ptp_vclock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ptp_vclock_unregister(struct ptp_vclock *vclock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81cd5260)
Location: drivers/ptp/ptp_vclock.c:224
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:unregister_vclock
  - drivers/ptp/ptp_sysfs.c:unregister_vclock
```
**Symbols:**

```
ffffffff81cd5260-ffffffff81cd52d8: ptp_vclock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ptp_vclock_unregister(struct ptp_vclock *vclock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81d3cef0)
Location: drivers/ptp/ptp_vclock.c:224
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:unregister_vclock
  - drivers/ptp/ptp_sysfs.c:unregister_vclock
```
**Symbols:**

```
ffffffff81d3cef0-ffffffff81d3cf68: ptp_vclock_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ptp_vclock_unregister(struct ptp_vclock *vclock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81df3850)
Location: drivers/ptp/ptp_vclock.c:224
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:unregister_vclock
  - drivers/ptp/ptp_sysfs.c:unregister_vclock
```
**Symbols:**

```
ffffffff81df3850-ffffffff81df38c8: ptp_vclock_unregister (STB_GLOBAL)
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
