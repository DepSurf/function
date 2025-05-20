# Function: <code>crng_initialize</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81567cc0)
Location: drivers/char/random.c:776
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff81567cc0-ffffffff81567d89: crng_initialize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815943f0)
Location: drivers/char/random.c:776
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff815943f0-ffffffff815944b9: crng_initialize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a8350)
Location: drivers/char/random.c:770
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff815a8350-ffffffff815a8419: crng_initialize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160ec60)
Location: drivers/char/random.c:769
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff8160ec60-ffffffff8160ed29: crng_initialize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816483c0)
Location: drivers/char/random.c:782
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:do_numa_crng_init
```
**Symbols:**

```
ffffffff816483c0-ffffffff81648489: crng_initialize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81666860)
Location: drivers/char/random.c:788
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:do_numa_crng_init
```
**Symbols:**

```
ffffffff81666860-ffffffff8166695c: crng_initialize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169c5a0)
Location: drivers/char/random.c:863
Inline: False
Direct callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff8169c5a0-ffffffff8169c6c2: crng_initialize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bf310)
Location: drivers/char/random.c:863
Inline: False
Direct callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff816bf310-ffffffff816bf432: crng_initialize (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108afeb8)
Location: drivers/char/random.c:863
Inline: False
Direct callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffff8000108afeb8-ffff8000108aff78: crng_initialize (STB_LOCAL)
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
In drivers/char/random.c (c15969c4)
Location: drivers/char/random.c:863
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000949640)
Location: drivers/char/random.c:863
Inline: False
Direct callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
c000000000949640-c000000000949820: crng_initialize (STB_LOCAL)
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
In drivers/char/random.c (ffffffe00002ffe6)
Location: drivers/char/random.c:863
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81684d60)
Location: drivers/char/random.c:863
Inline: False
Direct callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff81684d60-ffffffff81684e82: crng_initialize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81662a00)
Location: drivers/char/random.c:863
Inline: False
Direct callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff81662a00-ffffffff81662b22: crng_initialize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b3150)
Location: drivers/char/random.c:863
Inline: False
Direct callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff816b3150-ffffffff816b3272: crng_initialize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void crng_initialize(struct crng_state *crng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cd6d0)
Location: drivers/char/random.c:863
Inline: False
Direct callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff816cd6d0-ffffffff816cd7f2: crng_initialize (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
