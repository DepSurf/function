# Function: <code>ptp_convert_timestamp</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ktime_t ptp_convert_timestamp(const struct skb_shared_hwtstamps *hwtstamps, int vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_vclock.c (0)
Location: drivers/ptp/ptp_vclock.c:188
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff81d26231-ffffffff81d26246: ptp_convert_timestamp.cold (STB_LOCAL)
ffffffff819db0a0-ffffffff819db1b7: ptp_convert_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ktime_t ptp_convert_timestamp(const ktime_t *hwtstamp, int vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81b3e9b0)
Location: drivers/ptp/ptp_vclock.c:268
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff81b3e9b0-ffffffff81b3ea58: ptp_convert_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ktime_t ptp_convert_timestamp(const ktime_t *hwtstamp, int vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81cd4cf0)
Location: drivers/ptp/ptp_vclock.c:268
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff81cd4cf0-ffffffff81cd4d9f: ptp_convert_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ktime_t ptp_convert_timestamp(const ktime_t *hwtstamp, int vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81d3c950)
Location: drivers/ptp/ptp_vclock.c:268
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff81d3c950-ffffffff81d3c9ff: ptp_convert_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ktime_t ptp_convert_timestamp(const ktime_t *hwtstamp, int vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81df3290)
Location: drivers/ptp/ptp_vclock.c:268
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
```
**Symbols:**

```
ffffffff81df3290-ffffffff81df333f: ptp_convert_timestamp (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const ktime_t *hwtstamp</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct skb_shared_hwtstamps *hwtstamps</code>
</li>
</ul>
</details>
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
