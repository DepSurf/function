# Function: <code>_xfer_secondary_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81513230)
Location: drivers/char/random.c:995
Inline: False
```
**Symbols:**

```
ffffffff81513230-ffffffff815133ca: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81566cc0)
Location: drivers/char/random.c:1235
Inline: False
```
**Symbols:**

```
ffffffff81566cc0-ffffffff81566e53: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81593420)
Location: drivers/char/random.c:1235
Inline: False
```
**Symbols:**

```
ffffffff81593420-ffffffff815935b3: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a7220)
Location: drivers/char/random.c:1219
Inline: False
Direct callers:
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
ffffffff815a7220-ffffffff815a738c: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160db30)
Location: drivers/char/random.c:1218
Inline: False
Direct callers:
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
ffffffff8160db30-ffffffff8160dc9e: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81647620)
Location: drivers/char/random.c:1322
Inline: False
Direct callers:
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
ffffffff81647620-ffffffff8164778e: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81665ac0)
Location: drivers/char/random.c:1331
Inline: False
Direct callers:
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
ffffffff81665ac0-ffffffff81665c2e: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169b510)
Location: drivers/char/random.c:1408
Inline: False
Direct callers:
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
ffffffff8169b510-ffffffff8169b67b: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816be230)
Location: drivers/char/random.c:1408
Inline: False
Direct callers:
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
ffffffff816be230-ffffffff816be39b: _xfer_secondary_pool (STB_LOCAL)
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
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108aedf8)
Location: drivers/char/random.c:1408
Inline: False
Direct callers:
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
ffff8000108aedf8-ffff8000108aef7c: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09ab66c)
Location: drivers/char/random.c:1408
Inline: False
Direct callers:
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
c09ab66c-c09ab808: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000948bc0)
Location: drivers/char/random.c:1408
Inline: False
Direct callers:
  - drivers/char/random.c:push_to_pool
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
c000000000948bc0-c000000000948d90: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe000562966)
Location: drivers/char/random.c:1408
Inline: False
Direct callers:
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
ffffffe000562966-ffffffe000562aa4: _xfer_secondary_pool (STB_LOCAL)
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
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81683ca0)
Location: drivers/char/random.c:1408
Inline: False
Direct callers:
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
ffffffff81683ca0-ffffffff81683e0b: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81661920)
Location: drivers/char/random.c:1408
Inline: False
Direct callers:
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
ffffffff81661920-ffffffff81661a8b: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b2070)
Location: drivers/char/random.c:1408
Inline: False
Direct callers:
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
ffffffff816b2070-ffffffff816b21db: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cc520)
Location: drivers/char/random.c:1408
Inline: False
Direct callers:
  - drivers/char/random.c:xfer_secondary_pool
```
**Symbols:**

```
ffffffff816cc520-ffffffff816cc6a6: _xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
