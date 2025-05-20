# Function: <code>perf_event_release_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811809d0)
Location: kernel/events/core.c:3835
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_nmi_disable
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff811809d0-ffffffff811809dd: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81192b80)
Location: kernel/events/core.c:4088
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_nmi_disable
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff81192b80-ffffffff81192e0e: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a2360)
Location: kernel/events/core.c:4185
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:watchdog_nmi_disable
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff811a2360-ffffffff811a25e1: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a9af0)
Location: kernel/events/core.c:4272
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:watchdog_nmi_disable
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff811a9af0-ffffffff811a9d30: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bd340)
Location: kernel/events/core.c:4206
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff811bd340-ffffffff811bd61f: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dd590)
Location: kernel/events/core.c:4544
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff811dd590-ffffffff811dd86d: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ed990)
Location: kernel/events/core.c:4545
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff811ed990-ffffffff811edc6d: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812053c0)
Location: kernel/events/core.c:4579
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff812053c0-ffffffff812056d1: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81212750)
Location: kernel/events/core.c:4674
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff81212750-ffffffff81212a61: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123e540)
Location: kernel/events/core.c:4902
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff8123e540-ffffffff8123e906: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81248930)
Location: kernel/events/core.c:4981
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff81248930-ffffffff81248cfb: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124ca00)
Location: kernel/events/core.c:5065
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff8124ca00-ffffffff8124ccd7: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81289920)
Location: kernel/events/core.c:5171
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff81289920-ffffffff81289bf7: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812dd170)
Location: kernel/events/core.c:5069
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff812dd170-ffffffff812dd43b: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81345140)
Location: kernel/events/core.c:5284
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff81345140-ffffffff813453eb: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813761e0)
Location: kernel/events/core.c:5284
Inline: False
Direct callers:
  - kernel/watchdog_perf.c:watchdog_hardlockup_probe
  - kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff813761e0-ffffffff81376481: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139f4e0)
Location: kernel/events/core.c:5333
Inline: False
Direct callers:
  - kernel/watchdog_perf.c:watchdog_hardlockup_probe
  - kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff8139f4e0-ffffffff8139f781: perf_event_release_kernel (STB_GLOBAL)
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
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029cbf0)
Location: kernel/events/core.c:4674
Inline: False
Direct callers:
  - virt/kvm/arm/pmu.c:kvm_pmu_release_perf_event
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffff80001029cbf0-ffff80001029ce90: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cc1f8)
Location: kernel/events/core.c:4674
Inline: False
Direct callers:
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
c04cc1f8-c04cc4e8: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034d3d0)
Location: kernel/events/core.c:4674
Inline: False
Direct callers:
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
c00000000034d3d0-c00000000034d7a0: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cb354)
Location: kernel/events/core.c:4674
Inline: False
Direct callers:
  - kernel/events/core.c:perf_release
```
**Symbols:**

```
ffffffe0001cb354-ffffffe0001cb61c: perf_event_release_kernel (STB_GLOBAL)
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
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ada0)
Location: kernel/events/core.c:4674
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff8120ada0-ffffffff8120b0b1: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fdb80)
Location: kernel/events/core.c:4674
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff811fdb80-ffffffff811fde8b: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208b40)
Location: kernel/events/core.c:4674
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff81208b40-ffffffff81208e51: perf_event_release_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812178d0)
Location: kernel/events/core.c:4674
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_init
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/events/core.c:perf_release
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
```
**Symbols:**

```
ffffffff812178d0-ffffffff81217bea: perf_event_release_kernel (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
