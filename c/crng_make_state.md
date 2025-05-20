# Function: <code>crng_make_state</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void crng_make_state(u32 *chacha_state, u8 *random_data, size_t random_data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:289
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff81934e30-ffffffff81934ffb: crng_make_state (STB_LOCAL)
ffffffff81ec308e-ffffffff81ec30a3: crng_make_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crng_make_state(u32 *chacha_state, u8 *random_data, size_t random_data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a93420)
Location: drivers/char/random.c:317
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff81a93420-ffffffff81a93562: crng_make_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void crng_make_state(u32 *chacha_state, u8 *random_data, size_t random_data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81adeda0)
Location: drivers/char/random.c:317
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff81adeda0-ffffffff81adeee2: crng_make_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void crng_make_state(u32 *chacha_state, u8 *random_data, size_t random_data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b321c0)
Location: drivers/char/random.c:317
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:_get_random_bytes
```
**Symbols:**

```
ffffffff81b321c0-ffffffff81b32302: crng_make_state (STB_LOCAL)
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
