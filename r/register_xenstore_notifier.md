# Function: <code>register_xenstore_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff814cf270)
Location: drivers/xen/xenbus/xenbus_probe.c:658
Inline: True
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
```
**Symbols:**

```
ffffffff814cf270-ffffffff814cf29e: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8151fe70)
Location: drivers/xen/xenbus/xenbus_probe.c:658
Inline: True
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
```
**Symbols:**

```
ffffffff8151fe70-ffffffff8151fe9e: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8154c320)
Location: drivers/xen/xenbus/xenbus_probe.c:658
Inline: True
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
```
**Symbols:**

```
ffffffff8154c320-ffffffff8154c34e: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81560410)
Location: drivers/xen/xenbus/xenbus_probe.c:654
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff81560410-ffffffff8156043e: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c46c0)
Location: drivers/xen/xenbus/xenbus_probe.c:654
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff815c46c0-ffffffff815c46f4: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fcd40)
Location: drivers/xen/xenbus/xenbus_probe.c:657
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff815fcd40-ffffffff815fcd74: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81617e20)
Location: drivers/xen/xenbus/xenbus_probe.c:666
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff81617e20-ffffffff81617e54: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8164bae0)
Location: drivers/xen/xenbus/xenbus_probe.c:666
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff8164bae0-ffffffff8164bb14: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166df70)
Location: drivers/xen/xenbus/xenbus_probe.c:666
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff8166df70-ffffffff8166dfa4: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171e240)
Location: drivers/xen/xenbus/xenbus_probe.c:666
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff8171e240-ffffffff8171e274: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8173b1b0)
Location: drivers/xen/xenbus/xenbus_probe.c:667
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff8173b1b0-ffffffff8173b1e4: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171ecf0)
Location: drivers/xen/xenbus/xenbus_probe.c:733
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff8171ecf0-ffffffff8171ed24: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8179daa0)
Location: drivers/xen/xenbus/xenbus_probe.c:730
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff8179daa0-ffffffff8179dad4: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff818d7240)
Location: drivers/xen/xenbus/xenbus_probe.c:731
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff818d7240-ffffffff818d7288: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a29900)
Location: drivers/xen/xenbus/xenbus_probe.c:731
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff81a29900-ffffffff81a29948: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a73000)
Location: drivers/xen/xenbus/xenbus_probe.c:731
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff81a73000-ffffffff81a73048: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ac5160)
Location: drivers/xen/xenbus/xenbus_probe.c:731
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff81ac5160-ffffffff81ac51a8: register_xenstore_notifier (STB_GLOBAL)
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
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffff800010838b78)
Location: drivers/xen/xenbus/xenbus_probe.c:666
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffff800010838b78-ffff800010838be0: register_xenstore_notifier (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81633d80)
Location: drivers/xen/xenbus/xenbus_probe.c:736
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
```
**Symbols:**

```
ffffffff81633d80-ffffffff81633db4: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81661db0)
Location: drivers/xen/xenbus/xenbus_probe.c:666
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff81661db0-ffffffff81661de4: register_xenstore_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_xenstore_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8167c380)
Location: drivers/xen/xenbus/xenbus_probe.c:666
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_vcpu_hotplug_event
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff8167c380-ffffffff8167c3b4: register_xenstore_notifier (STB_GLOBAL)
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
