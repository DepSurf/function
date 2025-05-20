# Function: <code>unix_mknod</code>

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
In net/unix/af_unix.c (ffffffff817c0942)
Location: net/unix/af_unix.c:956
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (ffffffff8182d887)
Location: net/unix/af_unix.c:958
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (ffffffff8185f2d5)
Location: net/unix/af_unix.c:958
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (ffffffff81882bb0)
Location: net/unix/af_unix.c:959
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (ffffffff81904f60)
Location: net/unix/af_unix.c:960
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (ffffffff8195a698)
Location: net/unix/af_unix.c:950
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (ffffffff8198f388)
Location: net/unix/af_unix.c:957
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (ffffffff819faab6)
Location: net/unix/af_unix.c:954
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (ffffffff81a31746)
Location: net/unix/af_unix.c:966
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unix_mknod(const char *sun_path, umode_t mode, struct path *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b23a50)
Location: net/unix/af_unix.c:989
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81b23a50-ffffffff81b23b23: unix_mknod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unix_mknod(const char *sun_path, umode_t mode, struct path *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b32420)
Location: net/unix/af_unix.c:980
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81b32420-ffffffff81b324f3: unix_mknod (STB_LOCAL)
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
In net/unix/af_unix.c (ffffffff81b22451)
Location: net/unix/af_unix.c:981
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/unix/af_unix.c (ffff800010cf2940)
Location: net/unix/af_unix.c:966
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (c0df8774)
Location: net/unix/af_unix.c:966
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (c000000000e17db8)
Location: net/unix/af_unix.c:966
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (ffffffe00083e05c)
Location: net/unix/af_unix.c:966
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (ffffffff819d0dd6)
Location: net/unix/af_unix.c:966
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (ffffffff8198db96)
Location: net/unix/af_unix.c:966
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (ffffffff81a3b856)
Location: net/unix/af_unix.c:966
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
In net/unix/af_unix.c (ffffffff81a46ba6)
Location: net/unix/af_unix.c:966
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
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
</ul>
