# Function: <code>unregister_xenbus_watch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814cddc0)
Location: drivers/xen/xenbus/xenbus_xs.c:728
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:talk_to_otherend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff814cddc0-ffffffff814cdfd7: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151e930)
Location: drivers/xen/xenbus/xenbus_xs.c:723
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:talk_to_otherend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff8151e930-ffffffff8151eb52: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154ae10)
Location: drivers/xen/xenbus/xenbus_xs.c:737
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:talk_to_otherend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff8154ae10-ffffffff8154b032: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155f6e0)
Location: drivers/xen/xenbus/xenbus_xs.c:778
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:talk_to_otherend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff8155f6e0-ffffffff8155f92a: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c3980)
Location: drivers/xen/xenbus/xenbus_xs.c:781
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:talk_to_otherend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff815c3980-ffffffff815c3bca: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:783
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:talk_to_otherend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff815fc6cf-ffffffff815fc6ff: unregister_xenbus_watch.cold.11 (STB_LOCAL)
ffffffff815fc020-ffffffff815fc231: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:783
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:talk_to_otherend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff8161777f-ffffffff816177af: unregister_xenbus_watch.cold.11 (STB_LOCAL)
ffffffff816170d0-ffffffff816172e1: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:786
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:talk_to_otherend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff8164b41e-ffffffff8164b44e: unregister_xenbus_watch.cold (STB_LOCAL)
ffffffff8164ad90-ffffffff8164afb3: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:789
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:talk_to_otherend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff8166d8ae-ffffffff8166d8de: unregister_xenbus_watch.cold (STB_LOCAL)
ffffffff8166d220-ffffffff8166d443: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:789
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_resume
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
```
**Symbols:**

```
ffffffff8171dc0d-ffffffff8171dc25: unregister_xenbus_watch.cold (STB_LOCAL)
ffffffff8171d6d0-ffffffff8171d8b4: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:795
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_resume
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
```
**Symbols:**

```
ffffffff81c055be-ffffffff81c055d5: unregister_xenbus_watch.cold (STB_LOCAL)
ffffffff8173a690-ffffffff8173a87f: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:795
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_resume
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
**Symbols:**

```
ffffffff81bf7210-ffffffff81bf723d: unregister_xenbus_watch.cold (STB_LOCAL)
ffffffff8171de90-ffffffff8171e0f1: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:795
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_resume
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
**Symbols:**

```
ffffffff81cf611c-ffffffff81cf6149: unregister_xenbus_watch.cold (STB_LOCAL)
ffffffff8179cc40-ffffffff8179cea1: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:795
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_resume
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
**Symbols:**

```
ffffffff81ebe201-ffffffff81ebe218: unregister_xenbus_watch.cold (STB_LOCAL)
ffffffff818d6270-ffffffff818d647c: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a28750)
Location: drivers/xen/xenbus/xenbus_xs.c:795
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_resume
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
```
**Symbols:**

```
ffffffff81a28750-ffffffff81a28973: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a71e50)
Location: drivers/xen/xenbus/xenbus_xs.c:795
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_resume
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
```
**Symbols:**

```
ffffffff81a71e50-ffffffff81a72073: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac3fb0)
Location: drivers/xen/xenbus/xenbus_xs.c:795
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_resume
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
```
**Symbols:**

```
ffffffff81ac3fb0-ffffffff81ac41d3: unregister_xenbus_watch (STB_GLOBAL)
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
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffff800010837ad0)
Location: drivers/xen/xenbus/xenbus_xs.c:789
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:talk_to_otherend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffff800010837ad0-ffff800010837d9c: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:789
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_suspend
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:talk_to_otherend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff8163371e-ffffffff8163374e: unregister_xenbus_watch.cold (STB_LOCAL)
ffffffff81633090-ffffffff816332b3: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:789
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:talk_to_otherend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff816616ee-ffffffff8166171e: unregister_xenbus_watch.cold (STB_LOCAL)
ffffffff81661060-ffffffff81661283: unregister_xenbus_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void unregister_xenbus_watch(struct xenbus_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:789
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:talk_to_otherend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff8167bcbe-ffffffff8167bcee: unregister_xenbus_watch.cold (STB_LOCAL)
ffffffff8167b640-ffffffff8167b85f: unregister_xenbus_watch (STB_GLOBAL)
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
