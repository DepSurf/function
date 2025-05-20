# Function: <code>idr_get_next_ul</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819cf010)
Location: lib/idr.c:261
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff819cf010-ffffffff819cf08b: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a08580)
Location: lib/idr.c:257
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81a08580-ffffffff81a085f7: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a77f30)
Location: lib/idr.c:268
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81a77f30-ffffffff81a77fa7: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aaf220)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - lib/idr.c:idr_get_next
```
**Symbols:**

```
ffffffff81aaf220-ffffffff81aaf311: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815e8f50)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - lib/idr.c:idr_get_next
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
```
**Symbols:**

```
ffffffff815e8f50-ffffffff815e903a: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8160e000)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - lib/idr.c:idr_get_next
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
```
**Symbols:**

```
ffffffff8160e000-ffffffff8160e0ea: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815f1750)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - lib/idr.c:idr_get_next
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
```
**Symbols:**

```
ffffffff815f1750-ffffffff815f183a: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8165e8c0)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - lib/idr.c:idr_get_next
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
```
**Symbols:**

```
ffffffff8165e8c0-ffffffff8165e9aa: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81778110)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - lib/idr.c:idr_get_next
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_dump_walker
```
**Symbols:**

```
ffffffff81778110-ffffffff8177823d: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82020e70)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_dump_walker
  - lib/idr.c:idr_get_next
```
**Symbols:**

```
ffffffff82020e70-ffffffff82020f9d: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff820a0e90)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_dump_walker
  - lib/idr.c:idr_get_next
```
**Symbols:**

```
ffffffff820a0e90-ffffffff820a0fbd: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82178e70)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_seq_next
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pwm/core.c:pwmchip_find_by_name
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_dump_walker
  - lib/idr.c:idr_get_next
```
**Symbols:**

```
ffffffff82178e70-ffffffff82178f9d: idr_get_next_ul (STB_GLOBAL)
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
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffff800010d88a88)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - lib/idr.c:idr_get_next
```
**Symbols:**

```
ffff800010d88a88-ffff800010d88b88: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c0e83964)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - lib/idr.c:idr_get_next
```
**Symbols:**

```
c0e83964-c0e83a70: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c000000000ec9370)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - lib/idr.c:idr_get_next
```
**Symbols:**

```
c000000000ec9370-c000000000ec94f4: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffe0008b299e)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - lib/idr.c:idr_get_next
```
**Symbols:**

```
ffffffe0008b299e-ffffffe0008b2a50: idr_get_next_ul (STB_GLOBAL)
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
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a4e070)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - lib/idr.c:idr_get_next
```
**Symbols:**

```
ffffffff81a4e070-ffffffff81a4e161: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a0b160)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - lib/idr.c:idr_get_next
```
**Symbols:**

```
ffffffff81a0b160-ffffffff81a0b251: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aba460)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - lib/idr.c:idr_get_next
```
**Symbols:**

```
ffffffff81aba460-ffffffff81aba551: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *idr_get_next_ul(struct idr *idr, long unsigned int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81ac68b0)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - lib/idr.c:idr_get_next
```
**Symbols:**

```
ffffffff81ac68b0-ffffffff81ac69a1: idr_get_next_ul (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
