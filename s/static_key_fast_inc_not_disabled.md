# Function: <code>static_key_fast_inc_not_disabled</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool static_key_fast_inc_not_disabled(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:127
Inline: False
Direct callers:
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff82061ee2-ffffffff82061ef7: static_key_fast_inc_not_disabled.cold (STB_LOCAL)
ffffffff81354c20-ffffffff81354c8e: static_key_fast_inc_not_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool static_key_fast_inc_not_disabled(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:127
Inline: False
Direct callers:
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff820e1710-ffffffff820e1725: static_key_fast_inc_not_disabled.cold (STB_LOCAL)
ffffffff81386110-ffffffff8138617e: static_key_fast_inc_not_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool static_key_fast_inc_not_disabled(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:127
Inline: False
Direct callers:
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
```
**Symbols:**

```
ffffffff821be173-ffffffff821be188: static_key_fast_inc_not_disabled.cold (STB_LOCAL)
ffffffff813af5d0-ffffffff813af63e: static_key_fast_inc_not_disabled (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
