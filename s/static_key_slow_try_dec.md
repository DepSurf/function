# Function: <code>static_key_slow_try_dec</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812110c0)
Location: kernel/jump_label.c:220
Inline: True
```
**Symbols:**

```
ffffffff812110c0-ffffffff8121110a: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121ed00)
Location: kernel/jump_label.c:220
Inline: True
```
**Symbols:**

```
ffffffff8121ed00-ffffffff8121ed4a: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124a8f0)
Location: kernel/jump_label.c:220
Inline: False
Direct callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff8124a8f0-ffffffff8124a93e: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81254c90)
Location: kernel/jump_label.c:220
Inline: False
Direct callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff81254c90-ffffffff81254cde: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81259240)
Location: kernel/jump_label.c:220
Inline: False
Direct callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff81259240-ffffffff8125928e: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81294f00)
Location: kernel/jump_label.c:220
Inline: False
Direct callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff81294f00-ffffffff81294f4e: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812eaad0)
Location: kernel/jump_label.c:220
Inline: False
Direct callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff812eaad0-ffffffff812eab2d: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81354a30)
Location: kernel/jump_label.c:248
Inline: False
Direct callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff81354a30-ffffffff81354a8d: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81385dc0)
Location: kernel/jump_label.c:248
Inline: False
Direct callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff81385dc0-ffffffff81385e1d: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff813af280)
Location: kernel/jump_label.c:248
Inline: False
Direct callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff813af280-ffffffff813af2dd: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102ab108)
Location: kernel/jump_label.c:220
Inline: True
```
**Symbols:**

```
ffff8000102ab108-ffff8000102ab1a8: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035e9d0)
Location: kernel/jump_label.c:220
Inline: True
```
**Symbols:**

```
c00000000035e9d0-c00000000035ea68: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81217350)
Location: kernel/jump_label.c:220
Inline: True
```
**Symbols:**

```
ffffffff81217350-ffffffff8121739a: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8120a0b0)
Location: kernel/jump_label.c:220
Inline: True
```
**Symbols:**

```
ffffffff8120a0b0-ffffffff8120a0fa: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812150f0)
Location: kernel/jump_label.c:220
Inline: True
```
**Symbols:**

```
ffffffff812150f0-ffffffff8121513a: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool static_key_slow_try_dec(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812240c0)
Location: kernel/jump_label.c:220
Inline: True
```
**Symbols:**

```
ffffffff812240c0-ffffffff8122410a: static_key_slow_try_dec (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
