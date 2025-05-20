# Function: <code>drbg_seed_from_random</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int drbg_seed_from_random(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81664680)
Location: crypto/drbg.c:1092
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_generate
```
**Symbols:**

```
ffffffff81664680-ffffffff816647e4: drbg_seed_from_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int drbg_seed_from_random(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8171e9c0)
Location: crypto/drbg.c:1092
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_generate
```
**Symbols:**

```
ffffffff8171e9c0-ffffffff8171eb24: drbg_seed_from_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int drbg_seed_from_random(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8175a2d0)
Location: crypto/drbg.c:1092
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_generate
```
**Symbols:**

```
ffffffff8175a2d0-ffffffff8175a434: drbg_seed_from_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int drbg_seed_from_random(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8179c1d0)
Location: crypto/drbg.c:1076
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_generate
```
**Symbols:**

```
ffffffff8179c1d0-ffffffff8179c334: drbg_seed_from_random (STB_LOCAL)
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
