# Function: <code>extract_crng_user</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81567ed9)
Location: drivers/char/random.c:937
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (ffffffff81594619)
Location: drivers/char/random.c:937
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (ffffffff815a864e)
Location: drivers/char/random.c:921
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (ffffffff8160ef5e)
Location: drivers/char/random.c:920
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (ffffffff81648a5f)
Location: drivers/char/random.c:1029
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (ffffffff81666c7f)
Location: drivers/char/random.c:1042
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (ffffffff8169c9df)
Location: drivers/char/random.c:1119
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (ffffffff816bf74f)
Location: drivers/char/random.c:1119
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t extract_crng_user(void *buf, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81772dd0)
Location: drivers/char/random.c:1066
Inline: False
```
**Symbols:**

```
ffffffff81772dd0-ffffffff81772fc3: extract_crng_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t extract_crng_user(void *buf, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178ddc0)
Location: drivers/char/random.c:1066
Inline: False
```
**Symbols:**

```
ffffffff8178ddc0-ffffffff8178dfbd: extract_crng_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t extract_crng_user(void *buf, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81770770)
Location: drivers/char/random.c:1056
Inline: False
```
**Symbols:**

```
ffffffff81770770-ffffffff8177096d: extract_crng_user (STB_LOCAL)
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
In drivers/char/random.c (ffffffff817f61aa)
Location: drivers/char/random.c:1076
Inline: True
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108b0aa8)
Location: drivers/char/random.c:1119
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (c09aa440)
Location: drivers/char/random.c:1119
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (c0000000009483d4)
Location: drivers/char/random.c:1119
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (ffffffe00056221a)
Location: drivers/char/random.c:1119
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (ffffffff8168519f)
Location: drivers/char/random.c:1119
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (ffffffff81662e3f)
Location: drivers/char/random.c:1119
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (ffffffff816b358f)
Location: drivers/char/random.c:1119
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
In drivers/char/random.c (ffffffff816cdb0f)
Location: drivers/char/random.c:1119
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
