# Function: <code>try_to_generate_entropy</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bc75c)
Location: drivers/char/random.c:1758
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void try_to_generate_entropy();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81771150)
Location: drivers/char/random.c:1603
Inline: False
```
**Symbols:**

```
ffffffff81771150-ffffffff81771221: try_to_generate_entropy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void try_to_generate_entropy();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178c180)
Location: drivers/char/random.c:1602
Inline: False
```
**Symbols:**

```
ffffffff8178c180-ffffffff8178c251: try_to_generate_entropy (STB_LOCAL)
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
In drivers/char/random.c (ffffffff8176f0d8)
Location: drivers/char/random.c:1578
Inline: True
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
In drivers/char/random.c (ffffffff817f4915)
Location: drivers/char/random.c:1598
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void try_to_generate_entropy();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81ec2c87)
Location: drivers/char/random.c:1175
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read_iter
  - drivers/char/random.c:wait_for_random_bytes
```
**Symbols:**

```
ffffffff81ec2c87-ffffffff81ec2db5: try_to_generate_entropy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void try_to_generate_entropy();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a94cc0)
Location: drivers/char/random.c:1266
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read_iter
  - drivers/char/random.c:wait_for_random_bytes
```
**Symbols:**

```
ffffffff81a94cc0-ffffffff81a94f5c: try_to_generate_entropy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void try_to_generate_entropy();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81ae04e0)
Location: drivers/char/random.c:1266
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read_iter
  - drivers/char/random.c:wait_for_random_bytes
```
**Symbols:**

```
ffffffff81ae04e0-ffffffff81ae077c: try_to_generate_entropy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void try_to_generate_entropy();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b338e0)
Location: drivers/char/random.c:1266
Inline: False
Direct callers:
  - drivers/char/random.c:urandom_read_iter
  - drivers/char/random.c:wait_for_random_bytes
```
**Symbols:**

```
ffffffff81b338e0-ffffffff81b33b7c: try_to_generate_entropy (STB_LOCAL)
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
In drivers/char/random.c (ffff8000108ae074)
Location: drivers/char/random.c:1758
Inline: True
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
In drivers/char/random.c (c09a98bc)
Location: drivers/char/random.c:1758
Inline: True
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
In drivers/char/random.c (c0000000009460cc)
Location: drivers/char/random.c:1758
Inline: True
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
In drivers/char/random.c (ffffffe0005617ea)
Location: drivers/char/random.c:1758
Inline: True
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
In drivers/char/random.c (ffffffff816821bc)
Location: drivers/char/random.c:1758
Inline: True
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
In drivers/char/random.c (ffffffff8166003c)
Location: drivers/char/random.c:1758
Inline: True
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
In drivers/char/random.c (ffffffff816b059c)
Location: drivers/char/random.c:1758
Inline: True
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
In drivers/char/random.c (ffffffff816cacde)
Location: drivers/char/random.c:1758
Inline: True
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
