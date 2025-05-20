# Function: <code>__next_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_profile *__next_profile(struct aa_profile *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81374a40)
Location: security/apparmor/apparmorfs.c:853
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff81374a40-ffffffff81374af9: __next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_profile *__next_profile(struct aa_profile *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813aae30)
Location: security/apparmor/apparmorfs.c:1347
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff813aae30-ffffffff813aaeed: __next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_profile *__next_profile(struct aa_profile *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813c19b0)
Location: security/apparmor/apparmorfs.c:1453
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff813c19b0-ffffffff813c1a70: __next_profile (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff813d9015)
Location: security/apparmor/apparmorfs.c:1975
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff813ff085)
Location: security/apparmor/apparmorfs.c:2039
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff81430015)
Location: security/apparmor/apparmorfs.c:2036
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff8144cb65)
Location: security/apparmor/apparmorfs.c:2034
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff8147a9d5)
Location: security/apparmor/apparmorfs.c:2039
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff814946d5)
Location: security/apparmor/apparmorfs.c:2007
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff814ebefa)
Location: security/apparmor/apparmorfs.c:2126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff815092da)
Location: security/apparmor/apparmorfs.c:2123
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff8150fd0a)
Location: security/apparmor/apparmorfs.c:2124
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff8156d99a)
Location: security/apparmor/apparmorfs.c:2124
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff8160a04a)
Location: security/apparmor/apparmorfs.c:2144
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff816bc0ca)
Location: security/apparmor/apparmorfs.c:2333
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff816f4baa)
Location: security/apparmor/apparmorfs.c:2381
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff817318fa)
Location: security/apparmor/apparmorfs.c:2379
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
</details>
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
In security/apparmor/apparmorfs.c (ffff800010589e54)
Location: security/apparmor/apparmorfs.c:2007
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (c073af88)
Location: security/apparmor/apparmorfs.c:2007
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (c0000000006fb288)
Location: security/apparmor/apparmorfs.c:2007
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffe0003d93ce)
Location: security/apparmor/apparmorfs.c:2007
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff8148ccb5)
Location: security/apparmor/apparmorfs.c:2007
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff8147d6d5)
Location: security/apparmor/apparmorfs.c:2007
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff81488d55)
Location: security/apparmor/apparmorfs.c:2007
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff814a0895)
Location: security/apparmor/apparmorfs.c:2007
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:next_profile
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
</ul>
