# Function: <code>poll_schedule_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int poll_schedule_timeout(struct poll_wqueues *pwq, int state, ktime_t *expires, long unsigned int slack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81220c10)
Location: fs/select.c:234
Inline: False
Direct callers:
  - fs/select.c:do_select
  - fs/select.c:do_sys_poll
```
**Symbols:**

```
ffffffff81220c10-ffffffff81220c77: poll_schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int poll_schedule_timeout(struct poll_wqueues *pwq, int state, ktime_t *expires, long unsigned int slack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81248870)
Location: fs/select.c:234
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
**Symbols:**

```
ffffffff81248870-ffffffff812488d7: poll_schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int poll_schedule_timeout(struct poll_wqueues *pwq, int state, ktime_t *expires, long unsigned int slack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8125b8a0)
Location: fs/select.c:235
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
**Symbols:**

```
ffffffff8125b8a0-ffffffff8125b909: poll_schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int poll_schedule_timeout(struct poll_wqueues *pwq, int state, ktime_t *expires, long unsigned int slack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812686f0)
Location: fs/select.c:235
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
**Symbols:**

```
ffffffff812686f0-ffffffff81268759: poll_schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int poll_schedule_timeout(struct poll_wqueues *pwq, int state, ktime_t *expires, long unsigned int slack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128afa0)
Location: fs/select.c:236
Inline: False
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
**Symbols:**

```
ffffffff8128afa0-ffffffff8128b009: poll_schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812b1b20)
Location: fs/select.c:236
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
**Symbols:**

```
ffffffff812b1b20-ffffffff812b1b8a: poll_schedule_timeout.constprop.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812c6c40)
Location: fs/select.c:236
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
**Symbols:**

```
ffffffff812c6c40-ffffffff812c6caa: poll_schedule_timeout.constprop.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812e37c0)
Location: fs/select.c:236
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
**Symbols:**

```
ffffffff812e37c0-ffffffff812e382a: poll_schedule_timeout.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812f5200)
Location: fs/select.c:236
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
**Symbols:**

```
ffffffff812f5200-ffffffff812f526a: poll_schedule_timeout.constprop.0 (STB_LOCAL)
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
In fs/select.c (ffffffff8132dece)
Location: fs/select.c:236
Inline: True
Inline callers:
  - fs/select.c:do_select
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
In fs/select.c (ffffffff8133972b)
Location: fs/select.c:236
Inline: True
Inline callers:
  - fs/select.c:do_select
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
In fs/select.c (ffffffff8133fe28)
Location: fs/select.c:236
Inline: True
Inline callers:
  - fs/select.c:do_select
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
In fs/select.c (ffffffff8138d65e)
Location: fs/select.c:236
Inline: True
Inline callers:
  - fs/select.c:do_select
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
In fs/select.c (ffffffff8140eaef)
Location: fs/select.c:237
Inline: True
Inline callers:
  - fs/select.c:do_select
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
In fs/select.c (ffffffff8149965c)
Location: fs/select.c:237
Inline: True
Inline callers:
  - fs/select.c:do_select
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
In fs/select.c (ffffffff814ce765)
Location: fs/select.c:237
Inline: True
Inline callers:
  - fs/select.c:do_select
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
In fs/select.c (ffffffff815010a5)
Location: fs/select.c:237
Inline: True
Inline callers:
  - fs/select.c:do_select
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
In fs/select.c (ffff8000103a32e0)
Location: fs/select.c:236
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (c0584cbc)
Location: fs/select.c:236
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
**Symbols:**

```
c0584cbc-c0584d6c: poll_schedule_timeout.constprop.0 (STB_LOCAL)
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
In fs/select.c (c00000000049d08c)
Location: fs/select.c:236
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
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
In fs/select.c (ffffffe00026b2c8)
Location: fs/select.c:236
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812ed7e0)
Location: fs/select.c:236
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
**Symbols:**

```
ffffffff812ed7e0-ffffffff812ed84a: poll_schedule_timeout.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812de410)
Location: fs/select.c:236
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
**Symbols:**

```
ffffffff812de410-ffffffff812de47a: poll_schedule_timeout.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812eb5f0)
Location: fs/select.c:236
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
**Symbols:**

```
ffffffff812eb5f0-ffffffff812eb65a: poll_schedule_timeout.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812fc5e0)
Location: fs/select.c:236
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
**Symbols:**

```
ffffffff812fc5e0-ffffffff812fc64a: poll_schedule_timeout.constprop.0 (STB_LOCAL)
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
