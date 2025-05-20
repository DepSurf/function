# Function: <code>cec_mod_work</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cec_mod_work(long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff818d00d0)
Location: drivers/ras/cec.c:163
Inline: False
Direct callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff818d00d0-ffffffff818d0102: cec_mod_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_mod_work(long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff819024c0)
Location: drivers/ras/cec.c:164
Inline: False
Direct callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff819024c0-ffffffff819024f2: cec_mod_work (STB_LOCAL)
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
In drivers/ras/cec.c (ffffffff819d99d6)
Location: drivers/ras/cec.c:164
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
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
In drivers/ras/cec.c (ffffffff819d8d26)
Location: drivers/ras/cec.c:164
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
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
In drivers/ras/cec.c (ffffffff819bee86)
Location: drivers/ras/cec.c:164
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81a6e416)
Location: drivers/ras/cec.c:164
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81bdf2e6)
Location: drivers/ras/cec.c:164
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81d8a8b6)
Location: drivers/ras/cec.c:164
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81df8eb6)
Location: drivers/ras/cec.c:164
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81eaf5f6)
Location: drivers/ras/cec.c:164
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void cec_mod_work(long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff818a18f0)
Location: drivers/ras/cec.c:164
Inline: False
Direct callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff818a18f0-ffffffff818a1922: cec_mod_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_mod_work(long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff8185d060)
Location: drivers/ras/cec.c:164
Inline: False
Direct callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff8185d060-ffffffff8185d092: cec_mod_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_mod_work(long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff818f2ee0)
Location: drivers/ras/cec.c:164
Inline: False
Direct callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff818f2ee0-ffffffff818f2f12: cec_mod_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_mod_work(long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81913f80)
Location: drivers/ras/cec.c:164
Inline: False
Direct callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff81913f80-ffffffff81913fb2: cec_mod_work (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
