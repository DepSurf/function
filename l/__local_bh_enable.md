# Function: <code>__local_bh_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __local_bh_enable(unsigned int cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81084c80)
Location: kernel/softirq.c:127
Inline: False
Direct callers:
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff81084c80-ffffffff81084ccf: __local_bh_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __local_bh_enable(unsigned int cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81087fa0)
Location: kernel/softirq.c:127
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
```
**Symbols:**

```
ffffffff81087fa0-ffffffff81087fe7: __local_bh_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __local_bh_enable(unsigned int cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108cf00)
Location: kernel/softirq.c:138
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
```
**Symbols:**

```
ffffffff8108cf00-ffffffff8108cf47: __local_bh_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __local_bh_enable(unsigned int cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81089d30)
Location: kernel/softirq.c:138
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
  - kernel/softirq.c:_local_bh_enable
```
**Symbols:**

```
ffffffff81089d30-ffffffff81089d54: __local_bh_enable (STB_LOCAL)
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
In kernel/softirq.c (ffffffff81c00181)
Location: kernel/softirq.c:138
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff81c0017e)
Location: kernel/softirq.c:142
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff81e0018f)
Location: kernel/softirq.c:142
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff81e00188)
Location: kernel/softirq.c:142
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff81e00188)
Location: kernel/softirq.c:142
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff81e00175)
Location: kernel/softirq.c:142
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff82000167)
Location: kernel/softirq.c:149
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff82000162)
Location: kernel/softirq.c:337
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff8200017e)
Location: kernel/softirq.c:336
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff82200194)
Location: kernel/softirq.c:349
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff820d7065)
Location: kernel/softirq.c:349
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff8215a3f5)
Location: kernel/softirq.c:334
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff8223dc87)
Location: kernel/softirq.c:334
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffff800010081d5c)
Location: kernel/softirq.c:142
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (c0302a90)
Location: kernel/softirq.c:142
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (c000000000eeaf20)
Location: kernel/softirq.c:142
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffe0008cb47c)
Location: kernel/softirq.c:142
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff81e00188)
Location: kernel/softirq.c:142
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff81e0017c)
Location: kernel/softirq.c:142
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff81e00188)
Location: kernel/softirq.c:142
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
In kernel/softirq.c (ffffffff81e00188)
Location: kernel/softirq.c:142
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:_local_bh_enable
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
</ul>
