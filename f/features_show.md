# Function: <code>features_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct device *_d, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff814bedb0)
Location: drivers/virtio/virtio.c:44
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff814d38b0)
Location: drivers/xen/sys-hypervisor.c:327
Inline: False
```
**Symbols:**

```
ffffffff814bedb0-ffffffff814bee21: features_show (STB_LOCAL)
ffffffff814d38b0-ffffffff814d3935: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct device *_d, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8150eac0)
Location: drivers/virtio/virtio.c:44
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff815244e0)
Location: drivers/xen/sys-hypervisor.c:307
Inline: False
```
**Symbols:**

```
ffffffff8150eac0-ffffffff8150eb30: features_show (STB_LOCAL)
ffffffff815244e0-ffffffff81524565: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct device *_d, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8153ac20)
Location: drivers/virtio/virtio.c:44
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff815509a0)
Location: drivers/xen/sys-hypervisor.c:307
Inline: False
```
**Symbols:**

```
ffffffff8153ac20-ffffffff8153ac90: features_show (STB_LOCAL)
ffffffff815509a0-ffffffff81550a25: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct device *_d, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8154e440)
Location: drivers/virtio/virtio.c:44
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81565930)
Location: drivers/xen/sys-hypervisor.c:336
Inline: False
```
**Symbols:**

```
ffffffff8154e440-ffffffff8154e4b4: features_show (STB_LOCAL)
ffffffff81565930-ffffffff815659b7: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112cd10)
Location: kernel/cgroup/cgroup.c:5921
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff815b1b40)
Location: drivers/virtio/virtio.c:44
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff815c9ad0)
Location: drivers/xen/sys-hypervisor.c:336
Inline: False
```
**Symbols:**

```
ffffffff8112cd10-ffffffff8112cd34: features_show (STB_LOCAL)
ffffffff815b1b40-ffffffff815b1bb4: features_show (STB_LOCAL)
ffffffff815c9ad0-ffffffff815c9b57: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113bda0)
Location: kernel/cgroup/cgroup.c:5959
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff815e9f80)
Location: drivers/virtio/virtio.c:44
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81602370)
Location: drivers/xen/sys-hypervisor.c:336
Inline: True
```
**Symbols:**

```
ffffffff8113bda0-ffffffff8113bdc4: features_show (STB_LOCAL)
ffffffff815e9f80-ffffffff815e9ff4: features_show (STB_LOCAL)
ffffffff81602370-ffffffff816023f4: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81147620)
Location: kernel/cgroup/cgroup.c:6060
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81604490)
Location: drivers/virtio/virtio.c:44
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8161d460)
Location: drivers/xen/sys-hypervisor.c:336
Inline: True
```
**Symbols:**

```
ffffffff81147620-ffffffff81147644: features_show (STB_LOCAL)
ffffffff81604490-ffffffff81604504: features_show (STB_LOCAL)
ffffffff8161d460-ffffffff8161d4e4: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811528a0)
Location: kernel/cgroup/cgroup.c:6484
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81636e80)
Location: drivers/virtio/virtio.c:45
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81650680)
Location: drivers/xen/sys-hypervisor.c:333
Inline: False
```
**Symbols:**

```
ffffffff811528a0-ffffffff811528ed: features_show (STB_LOCAL)
ffffffff81636e80-ffffffff81636ef4: features_show (STB_LOCAL)
ffffffff81650680-ffffffff81650704: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115e4f0)
Location: kernel/cgroup/cgroup.c:6503
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81658be0)
Location: drivers/virtio/virtio.c:45
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81672c20)
Location: drivers/xen/sys-hypervisor.c:333
Inline: False
```
**Symbols:**

```
ffffffff8115e4f0-ffffffff8115e53d: features_show (STB_LOCAL)
ffffffff81658be0-ffffffff81658c54: features_show (STB_LOCAL)
ffffffff81672c20-ffffffff81672ca4: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116e870)
Location: kernel/cgroup/cgroup.c:6575
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff817092a0)
Location: drivers/virtio/virtio.c:45
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81723230)
Location: drivers/xen/sys-hypervisor.c:333
Inline: False
```
**Symbols:**

```
ffffffff8116e870-ffffffff8116e8da: features_show (STB_LOCAL)
ffffffff817092a0-ffffffff81709318: features_show (STB_LOCAL)
ffffffff81723230-ffffffff817232b1: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116b270)
Location: kernel/cgroup/cgroup.c:6567
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81726250)
Location: drivers/virtio/virtio.c:45
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8173fe70)
Location: drivers/xen/sys-hypervisor.c:333
Inline: False
```
**Symbols:**

```
ffffffff8116b270-ffffffff8116b2da: features_show (STB_LOCAL)
ffffffff81726250-ffffffff817262c8: features_show (STB_LOCAL)
ffffffff8173fe70-ffffffff8173fef1: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116bdf0)
Location: kernel/cgroup/cgroup.c:6545
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81709e60)
Location: drivers/virtio/virtio.c:45
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff817238c0)
Location: drivers/xen/sys-hypervisor.c:333
Inline: False
```
**Symbols:**

```
ffffffff8116bdf0-ffffffff8116be5a: features_show (STB_LOCAL)
ffffffff81709e60-ffffffff81709ed8: features_show (STB_LOCAL)
ffffffff817238c0-ffffffff81723941: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811919d0)
Location: kernel/cgroup/cgroup.c:6771
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff817856f0)
Location: drivers/virtio/virtio.c:46
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff817a2780)
Location: drivers/xen/sys-hypervisor.c:333
Inline: False
```
**Symbols:**

```
ffffffff811919d0-ffffffff81191a3a: features_show (STB_LOCAL)
ffffffff817856f0-ffffffff81785768: features_show (STB_LOCAL)
ffffffff817a2780-ffffffff817a2801: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c1360)
Location: kernel/cgroup/cgroup.c:6767
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff818bc460)
Location: drivers/virtio/virtio.c:47
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff818dca00)
Location: drivers/xen/sys-hypervisor.c:332
Inline: False
```
**Symbols:**

```
ffffffff811c1360-ffffffff811c13d0: features_show (STB_LOCAL)
ffffffff818bc460-ffffffff818bc4e4: features_show (STB_LOCAL)
ffffffff818dca00-ffffffff818dca92: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812039c0)
Location: kernel/cgroup/cgroup.c:7034
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81a0b090)
Location: drivers/virtio/virtio.c:47
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81a2fd30)
Location: drivers/xen/sys-hypervisor.c:332
Inline: False
```
**Symbols:**

```
ffffffff812039c0-ffffffff81203a49: features_show (STB_LOCAL)
ffffffff81a0b090-ffffffff81a0b11b: features_show (STB_LOCAL)
ffffffff81a2fd30-ffffffff81a2fdc2: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81218f20)
Location: kernel/cgroup/cgroup.c:7015
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81a53f20)
Location: drivers/virtio/virtio.c:47
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81a79540)
Location: drivers/xen/sys-hypervisor.c:335
Inline: False
```
**Symbols:**

```
ffffffff81218f20-ffffffff81218fa9: features_show (STB_LOCAL)
ffffffff81a53f20-ffffffff81a53fab: features_show (STB_LOCAL)
ffffffff81a79540-ffffffff81a795d2: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81230ab0)
Location: kernel/cgroup/cgroup.c:7056
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81aa4ba0)
Location: drivers/virtio/virtio.c:47
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81acb9b0)
Location: drivers/xen/sys-hypervisor.c:335
Inline: False
```
**Symbols:**

```
ffffffff81230ab0-ffffffff81230b66: features_show (STB_LOCAL)
ffffffff81aa4ba0-ffffffff81aa4c2b: features_show (STB_LOCAL)
ffffffff81acb9b0-ffffffff81acba42: features_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101ced28)
Location: kernel/cgroup/cgroup.c:6503
Inline: False
```
```
In drivers/virtio/virtio.c (ffff800010821070)
Location: drivers/virtio/virtio.c:45
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffff80001083d6f0)
Location: drivers/xen/sys-hypervisor.c:333
Inline: False
```
**Symbols:**

```
ffff8000101ced28-ffff8000101ced70: features_show (STB_LOCAL)
ffff800010821070-ffff800010821100: features_show (STB_LOCAL)
ffff80001083d6f0-ffff80001083d790: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c04121d8)
Location: kernel/cgroup/cgroup.c:6503
Inline: False
```
```
In drivers/virtio/virtio.c (c093ee78)
Location: drivers/virtio/virtio.c:45
Inline: False
```
**Symbols:**

```
c04121d8-c0412234: features_show (STB_LOCAL)
c093ee78-c093ef20: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000238d40)
Location: kernel/cgroup/cgroup.c:6503
Inline: False
```
```
In drivers/virtio/virtio.c (c0000000008ca6f0)
Location: drivers/virtio/virtio.c:45
Inline: False
```
**Symbols:**

```
c000000000238d40-c000000000238da0: features_show (STB_LOCAL)
c0000000008ca6f0-c0000000008ca7c4: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014955c)
Location: kernel/cgroup/cgroup.c:6503
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffe0005180aa)
Location: drivers/virtio/virtio.c:45
Inline: False
```
**Symbols:**

```
ffffffe00014955c-ffffffe000149592: features_show (STB_LOCAL)
ffffffe0005180aa-ffffffe000518134: features_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156b10)
Location: kernel/cgroup/cgroup.c:6503
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff8161ea80)
Location: drivers/virtio/virtio.c:45
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81638910)
Location: drivers/xen/sys-hypervisor.c:333
Inline: False
```
**Symbols:**

```
ffffffff81156b10-ffffffff81156b5d: features_show (STB_LOCAL)
ffffffff8161ea80-ffffffff8161eaf4: features_show (STB_LOCAL)
ffffffff81638910-ffffffff81638994: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81149e30)
Location: kernel/cgroup/cgroup.c:6503
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81613170)
Location: drivers/virtio/virtio.c:45
Inline: False
```
**Symbols:**

```
ffffffff81149e30-ffffffff81149e7d: features_show (STB_LOCAL)
ffffffff81613170-ffffffff816131e4: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811548e0)
Location: kernel/cgroup/cgroup.c:6503
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff8164ca20)
Location: drivers/virtio/virtio.c:45
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81666a60)
Location: drivers/xen/sys-hypervisor.c:333
Inline: False
```
**Symbols:**

```
ffffffff811548e0-ffffffff8115492d: features_show (STB_LOCAL)
ffffffff8164ca20-ffffffff8164ca94: features_show (STB_LOCAL)
ffffffff81666a60-ffffffff81666ae4: features_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t features_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811617e0)
Location: kernel/cgroup/cgroup.c:6503
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff816670f0)
Location: drivers/virtio/virtio.c:45
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81681010)
Location: drivers/xen/sys-hypervisor.c:333
Inline: False
```
**Symbols:**

```
ffffffff811617e0-ffffffff8116182d: features_show (STB_LOCAL)
ffffffff816670f0-ffffffff81667164: features_show (STB_LOCAL)
ffffffff81681010-ffffffff81681094: features_show (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kobject *kobj</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *_d</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device_attribute *attr</code> ➡️ <code>struct kobj_attribute *attr</code>
</li>
</ul>
</details>
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
