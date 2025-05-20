# Function: <code>copy_mc_fragile</code>

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

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
  - arch/x86/lib/copy_mc.c:copy_mc_fragile_handle_tail
```
**Symbols:**

```
ffffffff816217b0-ffffffff8162180a: copy_mc_fragile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
  - arch/x86/lib/copy_mc.c:copy_mc_fragile_handle_tail
```
**Symbols:**

```
ffffffff816050b0-ffffffff8160510a: copy_mc_fragile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
  - arch/x86/lib/copy_mc.c:copy_mc_fragile_handle_tail
```
**Symbols:**

```
ffffffff816739a0-ffffffff816739fa: copy_mc_fragile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void copy_mc_fragile();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc_64.S (ffffffff8178dfc0)
Location: arch/x86/lib/copy_mc_64.S
Inline: False
Direct callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
  - arch/x86/lib/copy_mc.c:copy_mc_fragile_handle_tail
```
**Symbols:**

```
ffffffff8178dfc0-ffffffff8178e033: copy_mc_fragile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void copy_mc_fragile();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc_64.S (ffffffff8204b800)
Location: arch/x86/lib/copy_mc_64.S
Inline: False
Direct callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
  - arch/x86/lib/copy_mc.c:copy_mc_fragile_handle_tail
```
**Symbols:**

```
ffffffff8204b800-ffffffff8204b873: copy_mc_fragile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void copy_mc_fragile();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc_64.S (ffffffff820ca0f0)
Location: arch/x86/lib/copy_mc_64.S
Inline: False
Direct callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
  - arch/x86/lib/copy_mc.c:copy_mc_fragile_handle_tail
```
**Symbols:**

```
ffffffff820ca0f0-ffffffff820ca163: copy_mc_fragile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void copy_mc_fragile();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc_64.S (ffffffff821a4a50)
Location: arch/x86/lib/copy_mc_64.S
Inline: False
Direct callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
  - arch/x86/lib/copy_mc.c:copy_mc_fragile_handle_tail
```
**Symbols:**

```
ffffffff821a4a50-ffffffff821a4ac3: copy_mc_fragile (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
