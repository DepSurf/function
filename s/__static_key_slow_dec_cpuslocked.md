# Function: <code>__static_key_slow_dec_cpuslocked</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key *key, long unsigned int rate_limit, struct delayed_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811c82f0)
Location: kernel/jump_label.c:183
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff811c82f0-ffffffff811c8370: __static_key_slow_dec_cpuslocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key *key, long unsigned int rate_limit, struct delayed_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811e8700)
Location: kernel/jump_label.c:184
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff811e8700-ffffffff811e8779: __static_key_slow_dec_cpuslocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key *key, long unsigned int rate_limit, struct delayed_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811f93c0)
Location: kernel/jump_label.c:205
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_deferred
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff811f93c0-ffffffff811f9441: __static_key_slow_dec_cpuslocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812113b0)
Location: kernel/jump_label.c:239
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff812113b0-ffffffff81211400: __static_key_slow_dec_cpuslocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121eff0)
Location: kernel/jump_label.c:239
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff8121eff0-ffffffff8121f040: __static_key_slow_dec_cpuslocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff8124b497)
Location: kernel/jump_label.c:239
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff8124ae40-ffffffff8124ae7d: __static_key_slow_dec_cpuslocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff812558f7)
Location: kernel/jump_label.c:239
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff81255230-ffffffff8125526d: __static_key_slow_dec_cpuslocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff81259dd7)
Location: kernel/jump_label.c:239
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff81259730-ffffffff8125976d: __static_key_slow_dec_cpuslocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff81295b64)
Location: kernel/jump_label.c:239
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff81295460-ffffffff8129549d: __static_key_slow_dec_cpuslocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff812eb867)
Location: kernel/jump_label.c:239
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff812eb240-ffffffff812eb280: __static_key_slow_dec_cpuslocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff81355977)
Location: kernel/jump_label.c:267
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff813552d0-ffffffff81355310: __static_key_slow_dec_cpuslocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff81386ff7)
Location: kernel/jump_label.c:267
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff813867c0-ffffffff81386800: __static_key_slow_dec_cpuslocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff813b0507)
Location: kernel/jump_label.c:267
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff813afc80-ffffffff813afcc0: __static_key_slow_dec_cpuslocked.part.0 (STB_LOCAL)
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
void __static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102ab348)
Location: kernel/jump_label.c:239
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffff8000102ab348-ffff8000102ab3d8: __static_key_slow_dec_cpuslocked (STB_LOCAL)
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
void __static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035ef90)
Location: kernel/jump_label.c:239
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
c00000000035ef90-c00000000035f04c: __static_key_slow_dec_cpuslocked (STB_LOCAL)
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
void __static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81217640)
Location: kernel/jump_label.c:239
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff81217640-ffffffff81217690: __static_key_slow_dec_cpuslocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8120a3a0)
Location: kernel/jump_label.c:239
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff8120a3a0-ffffffff8120a3f0: __static_key_slow_dec_cpuslocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812153e0)
Location: kernel/jump_label.c:239
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff812153e0-ffffffff81215430: __static_key_slow_dec_cpuslocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812243d0)
Location: kernel/jump_label.c:239
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
```
**Symbols:**

```
ffffffff812243d0-ffffffff81224420: __static_key_slow_dec_cpuslocked (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int rate_limit</code>
</li>
<li>
<b>Param removed. </b>
<code>struct delayed_work *work</code>
</li>
</ul>
</details>
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
