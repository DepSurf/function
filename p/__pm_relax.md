# Function: <code>__pm_relax</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155c090)
Location: drivers/base/power/wakeup.c:686
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_scan_ready_list
  - drivers/base/power/wakeup.c:wakeup_source_destroy
  - drivers/base/power/wakeup.c:pm_relax
```
**Symbols:**

```
ffffffff8155c090-ffffffff8155c106: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815ae290)
Location: drivers/base/power/wakeup.c:684
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
  - drivers/base/power/wakeup.c:pm_relax
  - drivers/base/power/wakeup.c:wakeup_source_destroy
```
**Symbols:**

```
ffffffff815ae290-ffffffff815ae306: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dd090)
Location: drivers/base/power/wakeup.c:684
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
  - drivers/base/power/wakeup.c:pm_relax
  - drivers/base/power/wakeup.c:wakeup_source_destroy
```
**Symbols:**

```
ffffffff815dd090-ffffffff815dd106: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f1a40)
Location: drivers/base/power/wakeup.c:684
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff815f1a40-ffffffff815f1ab0: __pm_relax.part.5 (STB_LOCAL)
ffffffff815f1ab0-ffffffff815f1ac7: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81659020)
Location: drivers/base/power/wakeup.c:685
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff81659020-ffffffff81659090: __pm_relax.part.6 (STB_LOCAL)
ffffffff81659090-ffffffff816590a7: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81694c50)
Location: drivers/base/power/wakeup.c:684
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff81694c50-ffffffff81694cc0: __pm_relax.part.10 (STB_LOCAL)
ffffffff81694cc0-ffffffff81694cd6: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b52e0)
Location: drivers/base/power/wakeup.c:690
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff816b52e0-ffffffff816b5350: __pm_relax.part.11 (STB_LOCAL)
ffffffff816b5350-ffffffff816b5366: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816eee80)
Location: drivers/base/power/wakeup.c:674
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff816eee80-ffffffff816eeef8: __pm_relax.part.0 (STB_LOCAL)
ffffffff816eef00-ffffffff816eef16: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817130a0)
Location: drivers/base/power/wakeup.c:694
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff817130a0-ffffffff81713118: __pm_relax.part.0 (STB_LOCAL)
ffffffff81713120-ffffffff81713136: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817ced00)
Location: drivers/base/power/wakeup.c:753
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff817ced00-ffffffff817ced7a: __pm_relax.part.0 (STB_LOCAL)
ffffffff817ced80-ffffffff817ced96: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e3300)
Location: drivers/base/power/wakeup.c:753
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff817e3300-ffffffff817e337a: __pm_relax.part.0 (STB_LOCAL)
ffffffff817e3380-ffffffff817e3396: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c76c0)
Location: drivers/base/power/wakeup.c:754
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff817c76c0-ffffffff817c773a: __pm_relax.part.0 (STB_LOCAL)
ffffffff817c7740-ffffffff817c7756: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81851a60)
Location: drivers/base/power/wakeup.c:755
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff81851a60-ffffffff81851ada: __pm_relax.part.0 (STB_LOCAL)
ffffffff81851ae0-ffffffff81851af6: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff819978e0)
Location: drivers/base/power/wakeup.c:755
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff819978e0-ffffffff8199795e: __pm_relax.part.0 (STB_LOCAL)
ffffffff81997960-ffffffff81997982: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b08880)
Location: drivers/base/power/wakeup.c:725
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff81b08880-ffffffff81b088fe: __pm_relax.part.0 (STB_LOCAL)
ffffffff81b08910-ffffffff81b08932: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b568a0)
Location: drivers/base/power/wakeup.c:720
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff81b568a0-ffffffff81b5691e: __pm_relax.part.0 (STB_LOCAL)
ffffffff81b56930-ffffffff81b56952: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81baee90)
Location: drivers/base/power/wakeup.c:720
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff81baee90-ffffffff81baef0e: __pm_relax.part.0 (STB_LOCAL)
ffffffff81baef20-ffffffff81baef42: __pm_relax (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffff800010904108)
Location: drivers/base/power/wakeup.c:694
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffff800010904108-ffff8000109041c0: __pm_relax.part.0 (STB_LOCAL)
ffff8000109041c0-ffff8000109041f0: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (c09ee1b4)
Location: drivers/base/power/wakeup.c:694
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
c09ee1b4-c09ee238: __pm_relax.part.0 (STB_LOCAL)
c09ee238-c09ee25c: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a2710)
Location: drivers/base/power/wakeup.c:694
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
c0000000009a2710-c0000000009a27d4: __pm_relax.part.0 (STB_LOCAL)
c0000000009a27e0-c0000000009a27fc: __pm_relax (STB_GLOBAL)
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
In fs/eventpoll.c (0)
Location: include/linux/pm_wakeup.h:174
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d9420)
Location: drivers/base/power/wakeup.c:694
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff816d9420-ffffffff816d9498: __pm_relax.part.0 (STB_LOCAL)
ffffffff816d94a0-ffffffff816d94b6: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b3a60)
Location: drivers/base/power/wakeup.c:694
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff816b3a60-ffffffff816b3ad8: __pm_relax.part.0 (STB_LOCAL)
ffffffff816b3ae0-ffffffff816b3af6: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81706d60)
Location: drivers/base/power/wakeup.c:694
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff81706d60-ffffffff81706dd8: __pm_relax.part.0 (STB_LOCAL)
ffffffff81706de0-ffffffff81706df6: __pm_relax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_relax(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81721790)
Location: drivers/base/power/wakeup.c:694
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff81721790-ffffffff81721808: __pm_relax.part.0 (STB_LOCAL)
ffffffff81721810-ffffffff81721826: __pm_relax (STB_GLOBAL)
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
