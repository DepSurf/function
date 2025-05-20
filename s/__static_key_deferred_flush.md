# Function: <code>__static_key_deferred_flush</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81210f30)
Location: kernel/jump_label.c:293
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff81210f30-ffffffff81210f77: __static_key_deferred_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121e780)
Location: kernel/jump_label.c:293
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff8121e780-ffffffff8121e7c7: __static_key_deferred_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124aa60)
Location: kernel/jump_label.c:293
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff8124aa60-ffffffff8124aaab: __static_key_deferred_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81254e00)
Location: kernel/jump_label.c:293
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff81254e00-ffffffff81254e4b: __static_key_deferred_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812593b0)
Location: kernel/jump_label.c:293
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff812593b0-ffffffff812593fb: __static_key_deferred_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:293
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff81cb9b95-ffffffff81cb9bb1: __static_key_deferred_flush.cold (STB_LOCAL)
ffffffff81295170-ffffffff812951c3: __static_key_deferred_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:293
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff81e6b18e-ffffffff81e6b1ab: __static_key_deferred_flush.cold (STB_LOCAL)
ffffffff812eaf00-ffffffff812eaf62: __static_key_deferred_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:321
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff82061f0c-ffffffff82061f29: __static_key_deferred_flush.cold (STB_LOCAL)
ffffffff81354f20-ffffffff81354f82: __static_key_deferred_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:321
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff820e173a-ffffffff820e1757: __static_key_deferred_flush.cold (STB_LOCAL)
ffffffff81386410-ffffffff81386472: __static_key_deferred_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:321
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff821be19d-ffffffff821be1ba: __static_key_deferred_flush.cold (STB_LOCAL)
ffffffff813af8d0-ffffffff813af932: __static_key_deferred_flush (STB_GLOBAL)
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
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102aa8e0)
Location: kernel/jump_label.c:293
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffff8000102aa8e0-ffff8000102aa94c: __static_key_deferred_flush (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035e5f0)
Location: kernel/jump_label.c:293
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
c00000000035e5f0-c00000000035e690: __static_key_deferred_flush (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81216dd0)
Location: kernel/jump_label.c:293
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff81216dd0-ffffffff81216e17: __static_key_deferred_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81209b30)
Location: kernel/jump_label.c:293
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff81209b30-ffffffff81209b77: __static_key_deferred_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81214b70)
Location: kernel/jump_label.c:293
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff81214b70-ffffffff81214bb7: __static_key_deferred_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __static_key_deferred_flush(void *key, struct delayed_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81223b20)
Location: kernel/jump_label.c:293
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_flush
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
```
**Symbols:**

```
ffffffff81223b20-ffffffff81223b67: __static_key_deferred_flush (STB_GLOBAL)
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
