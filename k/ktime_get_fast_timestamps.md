# Function: <code>ktime_get_fast_timestamps</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ktime_get_fast_timestamps(struct ktime_timestamps *snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811461d0)
Location: kernel/time/timekeeping.c:614
Inline: False
```
**Symbols:**

```
ffffffff811461d0-ffffffff811462ae: ktime_get_fast_timestamps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ktime_get_fast_timestamps(struct ktime_timestamps *snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81147230)
Location: kernel/time/timekeeping.c:614
Inline: False
```
**Symbols:**

```
ffffffff81147230-ffffffff8114730b: ktime_get_fast_timestamps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ktime_get_fast_timestamps(struct ktime_timestamps *snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:614
Inline: False
```
**Symbols:**

```
ffffffff81cb12da-ffffffff81cb12fc: ktime_get_fast_timestamps.cold (STB_LOCAL)
ffffffff8116ad20-ffffffff8116ae01: ktime_get_fast_timestamps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ktime_get_fast_timestamps(struct ktime_timestamps *snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:633
Inline: False
```
**Symbols:**

```
ffffffff81e62864-ffffffff81e62886: ktime_get_fast_timestamps.cold (STB_LOCAL)
ffffffff8119eb50-ffffffff8119ec32: ktime_get_fast_timestamps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ktime_get_fast_timestamps(struct ktime_timestamps *snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:633
Inline: False
```
**Symbols:**

```
ffffffff8205b6a0-ffffffff8205b6c2: ktime_get_fast_timestamps.cold (STB_LOCAL)
ffffffff811dd770-ffffffff811dd852: ktime_get_fast_timestamps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ktime_get_fast_timestamps(struct ktime_timestamps *snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:633
Inline: False
```
**Symbols:**

```
ffffffff820d9f5a-ffffffff820d9f7c: ktime_get_fast_timestamps.cold (STB_LOCAL)
ffffffff811f1c50-ffffffff811f1d25: ktime_get_fast_timestamps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ktime_get_fast_timestamps(struct ktime_timestamps *snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:633
Inline: False
```
**Symbols:**

```
ffffffff821b5859-ffffffff821b587b: ktime_get_fast_timestamps.cold (STB_LOCAL)
ffffffff81207d90-ffffffff81207e65: ktime_get_fast_timestamps (STB_GLOBAL)
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
