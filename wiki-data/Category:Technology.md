1.  Category:Technology

From lab to fab...cMUT could be a game changer for ultrasound images.
Advanced technology promises to advance the field of high-speed,
high-resolution visualization.

`Jun 1, 2013 Jan Provoost | Science Writer Harrie Tilmans `\
`MEMS Project Manager and Principal Scientist for imec Leuven, Belgium, www.imec.be  `\
`Medical Design`

ARTICLE FOCUS
-------------

-   Ultrasound imaging with built-in piezoelectric transducers
-   Micromachining on the substrate
-   The cMUT in medical applications

One of the candidate technologies to advance state-of-the-art ultrasound
imaging is the use of a capacitive micromachined ultrasonic transducer
(cMUT). With cMUT, ultrasound imaging could overcome some of the limits
inherent in currently used technology, bringing higher lateral and axial
resolution, higher speed, and even real-time 3D (or 4D) imaging to new
and improved diagnostic applications for areas such as ophthalmology,
dermatology, and cardiology

Intro
-----

The idea of using arrays of micromachined transducers for medical
imaging is not new. R&D has been going on in labs around throughout the
world for more than two decades, leading to proof-of-concept designs and
even operational 2D arrays of cMUT cells with integrated electronics.

But only recently have the production processes and tools have become
available to produce full-scale high-performance cMUT devices:
techniques to micromachine thousands to millions of microsized cMUT
cells together with CMOS chips that are powerful enough to drive these
cells and to read them. Today, the technology even allows the cMUT layer
to be integrated monolithically directly on top of the CMOS, fabricating
them as a single chip. This allows the realization of very large 2D
arrays (e.g., 100 × 100 elements) operating at rather high frequencies
(tens of MHz), which is not possible with conventional bulk
piezoelectric transducers.

Ultrasounds with bulk piezoelectric transducers
-----------------------------------------------

Ultrasound imaging (sonography) uses high-frequency sound waves of a few
MHz to a few tens of MHz to view soft tissues such as muscles and
internal organs. Since the first ultrasound systems were introduced, the
number of potential applications and image quality has grown steadily.
Because the technique is noninvasive and the sound waves are
nonionizing, it is now an essential tool in routine clinical practice.

<http://medicaldesign.com/site-files/medicaldesign.com/files/uploads/2013/06/Fig2_cmut_imec.gif>

`Figure 2. Illustration of small 1D cMUT array realized in imec’s SiGe-based cMUT technology.`

In a typical ultrasound exam, a handheld transducer is placed against
the skin. The transducer sends out high-frequency sound waves that
penetrate and reflect off of the body tissues and structures. The
returning sound waves, or echoes, are captured and reconstructed as an
image. That reconstruction is done based on the frequencies and
strengths (amplitudes) of the returned signals and the time it takes for
them to return to the transducer.

The crucial component to any ultrasound system is the ultrasound
transducer. This is a device with an array of elements or acoustic
pixels. Each pixel converts electrical energy to acoustic energy (i.e.
the ultrasound waves) and vice versa. The number and the size of the
acoustic pixels determine the imaging resolution, contrast, and field of
view achievable with a transducer array. In general, a higher number of
smaller pixels result in better resolution and contrast.

Today, conventional ultrasound transducers are based on one row of
64–256 elements made from piezoelectric ceramic materials. Further
reducing the dimensions of these cells and increasing their numbers has
a serious impact on the complexity of the fabrication of the
transducers. In other words: there is an economical and technological
limit to the realization of high-frequency and 2D arrays. And the latter
are essential for generating high-resolution 3D and 4D images (3D moving
in real-time).

Micromachined transducer systems such as cMUTs overcome the fabrication
limitations of these bulk piezoelectric-based transducers.

<http://medicaldesign.com/site-files/medicaldesign.com/files/uploads/2013/06/Fig3_cmut_crosssection_2-MAIN.gif>

`Figure 3. Cross-section detail (schema and picture) of CMUT cell realized on SiGe platform.`

An orchestra with thousands of little drums
-------------------------------------------

In cMUT technology, each cell resembles an ultrasmall drum. These drums
are made by micromachining on a silicon substrate. Each drum consists of
a cavity over which a thin membrane is suspended. The bottom of the
cavity and the membrane act as electrodes. If an AC signal superimposed
on a DC bias is applied across the electrodes of a cMUT drum, the
membrane starts to vibrate at a frequency close to the resonance
frequency of the membrane, thereby generating ultrasonic sound waves in
the medium around the cMUT. Conversely, if ultrasonic sound waves hit
the surface of the membrane, it also starts to vibrate, thereby
generating an AC electrical signal. In other words, cMUT cells can act
both as a transmitter and as a receiver for ultrasound.

With micromachining, the manufacturing complexity of the ultrasound
transducer does not depend on the ultrasound frequency of the
application that is targeted. It is sufficient to vary the lateral
dimension of the membranes and the thickness of the dielectric and
metallic films to achieve a cMUT operating in the desired frequency
band. High-resolution imaging needs frequencies of the order of 1 to
30MHz, requiring cells (and membranes) with lateral dimensions in the
order of tens of microns and the thicknesses of a few microns.

These cells are typically grouped in elements, each having a few tens of
cells. Such an element is the acoustic pixel (axel) of the ultrasound
sensor. These axels are in their turn organized as 1D or 2D arrays. An
example of a small 1D array, consisting of eight elements, fabricated at
imec is shown in the Figure 2.

All of these elements and their cells must be interconnected with the
front-end circuitry that drives them and reads out the echoed
ultrasound. To minimize the effects of the parasitic capacitances
induced by the interconnections, it is preferable to have the front-end
circuitry as close as possible to the cMUT element. But even if cables
with smaller capacitances are used, it is very challenging, if not
impossible, to address all of the array elements in a large cMUT array
and to route the bundle of cables to the electronics. This
interconnection challenge can be solved through monolithically
integrating the fabrication of the cMUT and front-end circuitry.

CMUT imaging in medical
-----------------------

High-frequency, high-resolution transducers are potentially easier to
fabricate with cMUT technology, which could make ultrasound available
for a wider range of applications. Also it could make high-end
applications more cost-effective for every point of care.

In ultrasound imaging, more details can be visualized as the frequency
and bandwidth of the ultrasound waves are increased. A 10 MHz transducer
with a 10 MHz bandwidth frequency response, and excited with a one-cycle
sine wave pulse at 10 MHz, for example, results in an axial resolution
of approximately 200 µm in the human body. Recent developments of
high-frequency arrays of transducers (up to and above 15 MHz) have
therefore allowed the use of ultrasound for new applications such as
ophthalmology or heart disease diagnosis, albeit at a high cost.

In ophthalmology, for example, ultrasound imaging allows the study of
the internal structures of the eye and orbit. It is indispensable in
those diseases in which it is not possible to optically observe the
inner structures of the eye, such as the retina or the vitreous body,
because of opacities of anterior structures (cornea, lens). Since the
ocular structures are very small, it is necessary to operate at very
high frequencies, in the range of 20 to 50 MHz. But because there are
only a few ultrasound transducer arrays operating at frequencies above
20 MHz, hospitals use mechanical scanning probes in which a
high-frequency ultrasonic transducer is physically rotated by a
mechanical system. This, however, limits the scanning speed to around 20
Hz.

Ultrasound imaging is also one of the diagnostic tools of choice for
heart diseases. The first cardiac ultrasound devices could only acquire
a single image line at a time (referred to as “M-mode” acquisition).
With this, doctors could study the basic morphological properties of the
heart such as the dimension of the left ventricular cavity or the
thickness of the segmental wall. In addition, the motion of the heart
during the cardiac cycle could be monitored. However, as the
field-of-view of this imaging approach remained very limited, correct
navigation through the heart and interpretation of the recordings were
difficult. Therefore, 2D ultrasound imaging (“B-mode” imaging) was
introduced by mechanically moving (i.e. tilting) the transducer between
subsequent line acquisitions. This mechanical motion of the transducer
was later replaced by electronic beam steering when phased-array
transducer technology was introduced. Cross-sectional images of the
heart can now be produced at typical frame rates of about 30 Hz.

Since then, the image quality and image resolution have continuously
improved. An ultrasound probe was made, for example, with a 2D
piezoelectric array closely interconnected to application specific
integrated circuits capable of performing part of the signal processing
in the probe itself. With monolithic cMUT technology, this integration
would be included in the chip package, with less fabrication complexity
and at a lower cost.

One approach of integrating the front-end electronics with the cMUT
array (i.e. monolithic integration) is to fabricate both the driving and
readout electronics together with the cMUT structure on the same
substrate wafer. This will lead to a better cMUT performance compared to
other integration schemes. That is, there is a better signal-to-noise
ratio through a reduced interconnect parasitic resistance and
capacitance, a smaller die size and package, and lower power
consumption. Such a monolithic approach is especially suited for
applications like cMUTS, where performance and miniaturization are of
key importance, and where hundreds of thousands or even millions
interconnections are needed between the cMUT array and a CMOS chip.

But monolithic integration is complex and challenging. Various
technologies, design expertise, application knowledge, and fabrication
capabilities have to collaborate more closely than routinely done in
either CMOS or MEMS (microelectromechanical system) fabrication.

imec has implemented an innovative approach to the monolithic
integration of MEMS structures such as the cMUTs. In this approach, imec
fabricates the cMUT structures on a planarized wafer after the CMOS
process has been completed. The cMUT processing and characteristics are
made independent of the CMOS technology with which they are combined.

Addressing temperature limitations
----------------------------------

A consequence of this method, however, is that the maximum process
temperature is limited to around 450°C because higher temperatures would
damage the underlying CMOS. Therefore, imec sets up its cMUT technology
platform and baseline process on 200-mm wafers making use of
poly-silicon-germanium (poly-SiGe), a material that can be processed at
these temperatures and that has mechanical properties for attaining
reliable and robust MEMS.

This SiGeMEMS platform allows for implementing all known cMUT design
flavors from the literature, such as uniform and bossed devices, with
single and dual electrodes, and in transmit and receive modes. The
consistent description of the modal resonant equivalent circuit; the
transduction between electrical, mechanical, and acoustic domains; and
the proper description of the acoustic load are key parts of the imec
model.

On the technology platform, imec has successfully built and tested cMUT
devices operating at frequencies in the 2- to 10-MHz range. Through a
unique stitching capability, imec is able to produce very large cMUT
arrays, the size of which is only limited by the wafer size. In
addition, imec has the capabilities for prototype fabrication,
reliability testing, acoustic testing and characterization, packaging,
and small volume fabrication.

Conclusion
----------

cMUT technology, especially when monolithically integrated with the CMOS
driving and readout chip, offers unique possibilities for medical
ultrasound imaging. It could be the basis of cost-effective ultrasound
transducers that bring current state-of-the-art techniques to
point-of-care applications. And it could advance the field of
high-speed, high-resolution visualization along with 3D/4D medical
imaging.

<Category:Articles>
