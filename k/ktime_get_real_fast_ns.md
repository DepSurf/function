# Function: <code>ktime_get_real_fast_ns</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110c680)
Location: kernel/time/timekeeping.c:527
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffffffff8110c680-ffffffff8110c72f: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811181f0)
Location: kernel/time/timekeeping.c:528
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffffffff811181f0-ffffffff8111829f: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81123810)
Location: kernel/time/timekeeping.c:535
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffffffff81123810-ffffffff811238bf: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112e000)
Location: kernel/time/timekeeping.c:541
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffffffff8112e000-ffffffff8112e093: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81139fb0)
Location: kernel/time/timekeeping.c:541
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffffffff81139fb0-ffffffff8113a043: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81148770)
Location: kernel/time/timekeeping.c:541
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81148770-ffffffff81148805: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81144be0)
Location: kernel/time/timekeeping.c:562
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81144be0-ffffffff81144c75: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81145ad0)
Location: kernel/time/timekeeping.c:562
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81145ad0-ffffffff81145b63: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:562
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81cb0c08-ffffffff81cb0c2a: ktime_get_real_fast_ns.cold (STB_LOCAL)
ffffffff81169570-ffffffff81169610: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:581
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81e621a0-ffffffff81e621c2: ktime_get_real_fast_ns.cold (STB_LOCAL)
ffffffff8119d1f0-ffffffff8119d296: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:581
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff8205b00f-ffffffff8205b031: ktime_get_real_fast_ns.cold (STB_LOCAL)
ffffffff811dbde0-ffffffff811dbe86: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:581
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffffffff820d9907-ffffffff820d9929: ktime_get_real_fast_ns.cold (STB_LOCAL)
ffffffff811f0410-ffffffff811f04b2: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:581
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffffffff821b5206-ffffffff821b5228: ktime_get_real_fast_ns.cold (STB_LOCAL)
ffffffff81206550-ffffffff812065f2: ktime_get_real_fast_ns (STB_GLOBAL)
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
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a3e80)
Location: kernel/time/timekeeping.c:541
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffff8000101a3e80-ffff8000101a3f18: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03edbb8)
Location: kernel/time/timekeeping.c:541
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
c03edbb8-c03edc94: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000205d90)
Location: kernel/time/timekeeping.c:541
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
c000000000205d90-c000000000205e68: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe000130a62)
Location: kernel/time/timekeeping.c:541
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffffffe000130a62-ffffffe000130aee: ktime_get_real_fast_ns (STB_GLOBAL)
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
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81132760)
Location: kernel/time/timekeeping.c:541
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffffffff81132760-ffffffff811327f3: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811251c0)
Location: kernel/time/timekeeping.c:541
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffffffff811251c0-ffffffff81125253: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81130480)
Location: kernel/time/timekeeping.c:541
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffffffff81130480-ffffffff81130513: ktime_get_real_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 ktime_get_real_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113cea0)
Location: kernel/time/timekeeping.c:541
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffffffff8113cea0-ffffffff8113cf33: ktime_get_real_fast_ns (STB_GLOBAL)
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
