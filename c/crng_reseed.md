# Function: <code>crng_reseed</code>

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
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81566640)
Location: drivers/char/random.c:821
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffffffff81566640-ffffffff8156681c: crng_reseed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81592da0)
Location: drivers/char/random.c:821
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffffffff81592da0-ffffffff81592f7c: crng_reseed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a6bb0)
Location: drivers/char/random.c:816
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffffffff815a6bb0-ffffffff815a6d7d: crng_reseed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160d4b0)
Location: drivers/char/random.c:815
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffffffff8160d4b0-ffffffff8160d680: crng_reseed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:910
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffffffff81646f80-ffffffff8164718f: crng_reseed (STB_LOCAL)
ffffffff816491c5-ffffffff816491fb: crng_reseed.cold.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:923
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffffffff81665420-ffffffff8166562f: crng_reseed (STB_LOCAL)
ffffffff816674d1-ffffffff81667507: crng_reseed.cold.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1000
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffffffff8169b060-ffffffff8169b265: crng_reseed (STB_LOCAL)
ffffffff8169cf6c-ffffffff8169cfa2: crng_reseed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1000
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffffffff816bdd90-ffffffff816bdf8e: crng_reseed (STB_LOCAL)
ffffffff816bfcd0-ffffffff816bfd06: crng_reseed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:948
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff81772270-ffffffff81772484: crng_reseed (STB_LOCAL)
ffffffff81773ba0-ffffffff81773bd6: crng_reseed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:948
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff8178d2e0-ffffffff8178d4f4: crng_reseed (STB_LOCAL)
ffffffff81c08535-ffffffff81c0856b: crng_reseed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:938
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff81770230-ffffffff817704a6: crng_reseed (STB_LOCAL)
ffffffff81bfa0fa-ffffffff81bfa130: crng_reseed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f5c10)
Location: drivers/char/random.c:989
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff817f5c10-ffffffff817f5e5a: crng_reseed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crng_reseed();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff819346c0)
Location: drivers/char/random.c:203
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:add_vmfork_randomness
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:_credit_init_bits
  - drivers/char/random.c:crng_make_state
  - drivers/char/random.c:random_init
```
**Symbols:**

```
ffffffff819346c0-ffffffff819347d1: crng_reseed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:249
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:add_vmfork_randomness
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init_early
```
**Symbols:**

```
ffffffff81a93ff0-ffffffff81a94164: crng_reseed (STB_LOCAL)
ffffffff820964da-ffffffff820964ee: crng_reseed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:249
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:add_vmfork_randomness
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init_early
```
**Symbols:**

```
ffffffff81adf810-ffffffff81adf984: crng_reseed (STB_LOCAL)
ffffffff82117422-ffffffff82117436: crng_reseed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:249
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:add_vmfork_randomness
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init_early
```
**Symbols:**

```
ffffffff81b32c30-ffffffff81b32da4: crng_reseed (STB_LOCAL)
ffffffff821f5197-ffffffff821f51ab: crng_reseed.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108ae7d8)
Location: drivers/char/random.c:1000
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffff8000108ae7d8-ffff8000108aead4: crng_reseed (STB_LOCAL)
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
In drivers/char/random.c (c09aa0a4)
Location: drivers/char/random.c:1000
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
c09aa0a4-c09aa2ac: crng_reseed.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000946b60)
Location: drivers/char/random.c:1000
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
c000000000946b60-c000000000946edc: crng_reseed (STB_LOCAL)
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
In drivers/char/random.c (ffffffe000561ebc)
Location: drivers/char/random.c:1000
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffffffe000561ebc-ffffffe000562086: crng_reseed.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1000
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffffffff81683800-ffffffff816839fe: crng_reseed (STB_LOCAL)
ffffffff81685720-ffffffff81685756: crng_reseed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1000
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffffffff81661480-ffffffff8166167e: crng_reseed (STB_LOCAL)
ffffffff816633c0-ffffffff816633f6: crng_reseed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1000
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffffffff816b1bd0-ffffffff816b1dce: crng_reseed (STB_LOCAL)
ffffffff816b3b10-ffffffff816b3b46: crng_reseed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void crng_reseed(struct crng_state *crng, struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1000
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:credit_entropy_bits
```
**Symbols:**

```
ffffffff816cc070-ffffffff816cc26e: crng_reseed (STB_LOCAL)
ffffffff816ce070-ffffffff816ce0a6: crng_reseed.cold (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct crng_state *crng</code>
</li>
<li>
<b>Param removed. </b>
<code>struct entropy_store *r</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct work_struct *work</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
