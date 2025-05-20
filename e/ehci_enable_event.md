# Function: <code>ehci_enable_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81631aa0)
Location: drivers/usb/host/ehci-timer.c:84
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff81631aa0-ffffffff81631b05: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81692250)
Location: drivers/usb/host/ehci-timer.c:85
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff81692250-ffffffff816922b5: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c16c0)
Location: drivers/usb/host/ehci-timer.c:85
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff816c16c0-ffffffff816c1725: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816d5b00)
Location: drivers/usb/host/ehci-timer.c:85
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff816d5b00-ffffffff816d5b65: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817421f0)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff817421f0-ffffffff81742255: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81782d20)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff81782d20-ffffffff81782d83: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817a9c80)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
```
**Symbols:**

```
ffffffff817a9c80-ffffffff817a9ce3: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817e8e20)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff817e8e20-ffffffff817e8e86: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81819ce0)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff81819ce0-ffffffff81819d46: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f200e)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:scan_async
  - drivers/usb/host/ehci-hcd.c:scan_async
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
**Symbols:**

```
ffffffff818ea850-ffffffff818ea8b6: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818faf2e)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:scan_async
  - drivers/usb/host/ehci-hcd.c:scan_async
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
**Symbols:**

```
ffffffff818f3740-ffffffff818f37a6: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818ddcee)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
**Symbols:**

```
ffffffff818d6ef0-ffffffff818d6f56: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8197980e)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
**Symbols:**

```
ffffffff819714f0-ffffffff819715b0: ehci_enable_event (STB_LOCAL)
ffffffff81d1e8ab-ffffffff81d1e8c4: ehci_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad6efa)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
**Symbols:**

```
ffffffff81acd1a0-ffffffff81acd280: ehci_enable_event (STB_LOCAL)
ffffffff81eea4c6-ffffffff81eea4df: ehci_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c61c7a)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
**Symbols:**

```
ffffffff81c57b30-ffffffff81c57c10: ehci_enable_event (STB_LOCAL)
ffffffff820a5325-ffffffff820a533e: ehci_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc901b)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
**Symbols:**

```
ffffffff81cbf150-ffffffff81cbf230: ehci_enable_event (STB_LOCAL)
ffffffff8212684a-ffffffff82126863: ehci_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7defb)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
**Symbols:**

```
ffffffff81d73f10-ffffffff81d73ff0: ehci_enable_event (STB_LOCAL)
ffffffff8220805b-ffffffff82208074: ehci_enable_event.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a52f38)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffff800010a52f38-ffff800010a52ff8: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b25e60)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
c0b25e60-c0b25f08: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b1cd50)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
c000000000b1cd50-c000000000b1ce50: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe00066fade)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffe00066fade-ffffffe00066fb8c: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d20c0)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff817d20c0-ffffffff817d2126: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8180eb60)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff8180eb60-ffffffff8180ebc6: ehci_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ehci_enable_event(struct ehci_hcd *ehci, unsigned int event, bool resched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81829630)
Location: drivers/usb/host/ehci-timer.c:76
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff81829630-ffffffff81829696: ehci_enable_event (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
