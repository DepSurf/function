# Function: <code>tcp_parse_mss_option</code>

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
In net/ipv4/tcp_input.c (ffffffff819c5419)
Location: net/ipv4/tcp_input.c:3795
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u16 tcp_parse_mss_option(const struct tcphdr *th, u16 user_mss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aafc70)
Location: net/ipv4/tcp_input.c:3789
Inline: False
```
**Symbols:**

```
ffffffff81aafc70-ffffffff81aafcfe: tcp_parse_mss_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u16 tcp_parse_mss_option(const struct tcphdr *th, u16 user_mss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abaac0)
Location: net/ipv4/tcp_input.c:3918
Inline: False
```
**Symbols:**

```
ffffffff81abaac0-ffffffff81abab4e: tcp_parse_mss_option (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff81aa675b)
Location: net/ipv4/tcp_input.c:3925
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
In net/ipv4/tcp_input.c (ffffffff81b62b4b)
Location: net/ipv4/tcp_input.c:3959
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81cf117f)
Location: net/ipv4/tcp_input.c:3977
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 tcp_parse_mss_option(const struct tcphdr *th, u16 user_mss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb5100)
Location: net/ipv4/tcp_input.c:3990
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_raw_gen_syncookie_ipv6
  - net/core/filter.c:bpf_tcp_raw_gen_syncookie_ipv4
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
```
**Symbols:**

```
ffffffff81eb5100-ffffffff81eb519f: tcp_parse_mss_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 tcp_parse_mss_option(const struct tcphdr *th, u16 user_mss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f13530)
Location: net/ipv4/tcp_input.c:3995
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_raw_gen_syncookie_ipv6
  - net/core/filter.c:bpf_tcp_raw_gen_syncookie_ipv4
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
```
**Symbols:**

```
ffffffff81f13530-ffffffff81f135cf: tcp_parse_mss_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 tcp_parse_mss_option(const struct tcphdr *th, u16 user_mss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd7a10)
Location: net/ipv4/tcp_input.c:4073
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_raw_gen_syncookie_ipv6
  - net/core/filter.c:bpf_tcp_raw_gen_syncookie_ipv4
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
```
**Symbols:**

```
ffffffff81fd7a10-ffffffff81fd7aaf: tcp_parse_mss_option (STB_GLOBAL)
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
In net/ipv4/tcp_input.c (ffff800010c793f8)
Location: net/ipv4/tcp_input.c:3795
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
In net/ipv4/tcp_input.c (c0d86ef4)
Location: net/ipv4/tcp_input.c:3795
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
In net/ipv4/tcp_input.c (c000000000d80790)
Location: net/ipv4/tcp_input.c:3795
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
In net/ipv4/tcp_input.c (ffffffe0007db10a)
Location: net/ipv4/tcp_input.c:3795
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
In net/ipv4/tcp_input.c (ffffffff81965289)
Location: net/ipv4/tcp_input.c:3795
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
In net/ipv4/tcp_input.c (ffffffff8191ed79)
Location: net/ipv4/tcp_input.c:3795
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
In net/ipv4/tcp_input.c (ffffffff819cfa59)
Location: net/ipv4/tcp_input.c:3795
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
In net/ipv4/tcp_input.c (ffffffff819d95e9)
Location: net/ipv4/tcp_input.c:3795
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
