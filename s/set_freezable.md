# Function: <code>set_freezable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810e9c40)
Location: kernel/freezer.c:164
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/ksm.c:ksm_scan_thread
  - mm/huge_memory.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff810e9c40-ffffffff810e9caa: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f09a0)
Location: kernel/freezer.c:164
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff810f09a0-ffffffff810f0a0a: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f7b00)
Location: kernel/freezer.c:164
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff810f7b00-ffffffff810f7b6a: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f99d0)
Location: kernel/freezer.c:164
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff810f99d0-ffffffff810f9a3a: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81104490)
Location: kernel/freezer.c:164
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff81104490-ffffffff811044fa: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8110f290)
Location: kernel/freezer.c:164
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff8110f290-ffffffff8110f2f9: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8111a8d0)
Location: kernel/freezer.c:166
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff8111a8d0-ffffffff8111a939: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81124fd0)
Location: kernel/freezer.c:167
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff81124fd0-ffffffff8112503f: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81130f90)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff81130f90-ffffffff81130fff: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81140350)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff81140350-ffffffff811403c3: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8113c6c0)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff8113c6c0-ffffffff8113c733: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8113d910)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff8113d910-ffffffff8113d983: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81160a90)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff81160a90-ffffffff81160b03: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81193810)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff81193810-ffffffff81193883: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811d11b0)
Location: kernel/freezer.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff811d11b0-ffffffff811d121b: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811e5420)
Location: kernel/freezer.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff811e5420-ffffffff811e548b: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811fb1d0)
Location: kernel/freezer.c:218
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff811fb1d0-ffffffff811fb23b: set_freezable (STB_GLOBAL)
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
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffff800010198218)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffff800010198218-ffff8000101982fc: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (c03e3250)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
c03e3250-c03e32f0: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (c0000000001f8150)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal.c:kopald
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
c0000000001f8150-c0000000001f8230: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffe000128f6e)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffe000128f6e-ffffffe000129028: set_freezable (STB_GLOBAL)
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
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81129740)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff81129740-ffffffff811297af: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8111bfd0)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff8111bfd0-ffffffff8111c039: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81127460)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff81127460-ffffffff811274cf: set_freezable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool set_freezable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81133ab0)
Location: kernel/freezer.c:161
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff81133ab0-ffffffff81133b0c: set_freezable (STB_GLOBAL)
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
