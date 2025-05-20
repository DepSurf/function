# Function: <code>tasklet_hrtimer_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tasklet_hrtimer_init(struct tasklet_hrtimer *ttimer, enum hrtimer_restart (*function)(struct hrtimer *), clockid_t which_clock, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81084d90)
Location: kernel/softirq.c:622
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff81084d90-ffffffff81084de2: tasklet_hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tasklet_hrtimer_init(struct tasklet_hrtimer *ttimer, enum hrtimer_restart (*function)(struct hrtimer *), clockid_t which_clock, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810880a0)
Location: kernel/softirq.c:622
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff810880a0-ffffffff810880f2: tasklet_hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tasklet_hrtimer_init(struct tasklet_hrtimer *ttimer, enum hrtimer_restart (*function)(struct hrtimer *), clockid_t which_clock, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108d000)
Location: kernel/softirq.c:636
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff8108d000-ffffffff8108d052: tasklet_hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tasklet_hrtimer_init(struct tasklet_hrtimer *ttimer, enum hrtimer_restart (*function)(struct hrtimer *), clockid_t which_clock, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81089e00)
Location: kernel/softirq.c:636
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff81089e00-ffffffff81089e4f: tasklet_hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tasklet_hrtimer_init(struct tasklet_hrtimer *ttimer, enum hrtimer_restart (*function)(struct hrtimer *), clockid_t which_clock, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81090b40)
Location: kernel/softirq.c:626
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff81090b40-ffffffff81090b8f: tasklet_hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tasklet_hrtimer_init(struct tasklet_hrtimer *ttimer, enum hrtimer_restart (*function)(struct hrtimer *), clockid_t which_clock, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810946f0)
Location: kernel/softirq.c:613
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff810946f0-ffffffff8109473f: tasklet_hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tasklet_hrtimer_init(struct tasklet_hrtimer *ttimer, enum hrtimer_restart (*function)(struct hrtimer *), clockid_t which_clock, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8109ca50)
Location: kernel/softirq.c:614
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff8109ca50-ffffffff8109ca9f: tasklet_hrtimer_init (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
