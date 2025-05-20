# Function: <code>_crng_backtrack_protect</code>

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
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815665c0)
Location: drivers/char/random.c:904
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff815665c0-ffffffff81566638: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81592d20)
Location: drivers/char/random.c:904
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81592d20-ffffffff81592d98: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a7ee0)
Location: drivers/char/random.c:888
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff815a7ee0-ffffffff815a7f51: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160e7e0)
Location: drivers/char/random.c:887
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff8160e7e0-ffffffff8160e851: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u32 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81648140)
Location: drivers/char/random.c:996
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81648140-ffffffff816481a7: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816665e0)
Location: drivers/char/random.c:1009
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff816665e0-ffffffff81666647: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169aff0)
Location: drivers/char/random.c:1086
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff8169aff0-ffffffff8169b057: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bdd20)
Location: drivers/char/random.c:1086
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff816bdd20-ffffffff816bdd87: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817735b3)
Location: drivers/char/random.c:1033
Inline: True
Inline callers:
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:crng_reseed
Direct callers:
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_crng_user
```
**Symbols:**

```
ffffffff81772d30-ffffffff81772dc5: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178e56e)
Location: drivers/char/random.c:1033
Inline: True
Inline callers:
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:crng_reseed
Direct callers:
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_crng_user
```
**Symbols:**

```
ffffffff8178dd20-ffffffff8178ddb5: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81770ddd)
Location: drivers/char/random.c:1023
Inline: True
Inline callers:
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:crng_reseed
Direct callers:
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_crng_user
```
**Symbols:**

```
ffffffff817706d0-ffffffff81770765: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f68eb)
Location: drivers/char/random.c:1051
Inline: True
Inline callers:
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:crng_reseed
Direct callers:
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff817f60d0-ffffffff817f6165: _crng_backtrack_protect (STB_LOCAL)
```
</details>
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
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108afbc8)
Location: drivers/char/random.c:1086
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffff8000108afbc8-ffff8000108afcc4: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (c09aa364)
Location: drivers/char/random.c:1086
Inline: True
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
c09aa364-c09aa3e0: _crng_backtrack_protect.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000947df0)
Location: drivers/char/random.c:1086
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
c000000000947df0-c000000000947ebc: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffe000562148)
Location: drivers/char/random.c:1086
Inline: True
Direct callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffe000562148-ffffffe0005621d4: _crng_backtrack_protect.constprop.0 (STB_LOCAL)
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
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81683790)
Location: drivers/char/random.c:1086
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81683790-ffffffff816837f7: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81661410)
Location: drivers/char/random.c:1086
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81661410-ffffffff81661477: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b1b60)
Location: drivers/char/random.c:1086
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff816b1b60-ffffffff816b1bc7: _crng_backtrack_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _crng_backtrack_protect(struct crng_state *crng, __u8 *tmp, int used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cc000)
Location: drivers/char/random.c:1086
Inline: False
Direct callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff816cc000-ffffffff816cc067: _crng_backtrack_protect (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>__u8 *tmp</code> ➡️ <code>__u32 *tmp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>__u32 *tmp</code> ➡️ <code>__u8 *tmp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
