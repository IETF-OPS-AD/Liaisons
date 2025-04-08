We would like to thank the ITU-T-SG-11 for informing the IETF about the new work item
QSTR.MVC "Method for Verifying Conformance to SRv6" [1]. Specifically, we appreciate
that the ITU is soliciting feedback for a work related to an IETF-developed
technology: Segment Routing over IPv6 (SRv6). We acknoweldge that the technical report
does not aim to alter any SRv6 specification or seek to specify new SRv6 requirements outside of IETF's work.

The specifications listed as "Core SRv6 Standards" in the attached document to
the LS are a subset of SRv6-related Proposed Standards published so far by the IETF. The IETF does not
identify a subset of SRv6-related specifications as "Core SRv6 Standards". 
There are several Working Groups (WGs) in the IETF 
(mainly SPRING, 6MAN, BMWG, BESS, IDR, LSR, PCE, RTGWG, TEAS, and OPSAWG) that are working
on SRv6-related specifications. The links to all active IETF WGs can be found at [2].
Further, the list of RFCs published by each of the WG are available on each WG's page.

Unlike what is stated in the report, some of the listed RFCs (e.g., RFC 8665, 8666, and 8667) do not
apply for SRv6 but for SR-MPLS. Some RFCs (e.g., RFC 9256) apply for both SRv6 and SR-MPLS.
A review of the RFCs listed on the WGs pages will provide information on their applicability to SRv6.
Also, the correct names for these RFCs are as follows:
   * RFC 8665: OSPF Extensions for Segment Routing
   * RFC 8666: OSPFv3 Extensions for Segment Routing
   * RFC 8667: IS-IS Extensions for Segment Routing
Note that some other SRv6-related specifications (notably, "Compressed SRv6 Segment
the publication process with the RFC Editor.

Note that some other SRv6-related specifications are being finalized by SPRING.
Notably, "Compressed SRv6 Segment List Encoding (CSID)" [3] has been approved
and is planned for publication by the IETF in the coming few months.
When referring to aspects of the IETF standards as "mandatory" or "optional", it is recommended to 
provide a reference to the specific section and text from the specific RFC. This will
avoid misalignment with IETF standards. E.g., RFC 8754 does not specify the usage of Tag in 
the SRH (it only introduces the Tag field in the SRH) but the ITU document marks 
'Packet Tagging and Tag Processing' as mandatory. There are other similar misalignments.

While ensuring better interoperability is one of the key objectives of the IETF
specifications, the IETF does not produce formal conformance test suites per se. However, the IETF
has a WG that is chartered for Benchmarking Methodology (BMWG WG) [4].

For information, the BMWG is actively working on an SR-related benchmarking
methodology specification [5] with a focus on performance for both SRv6 and SR-MPLS.
This specification is planned for publication by the end of 2025.
 
For future collaboration on these matters, we encourage the use of BMWG WG mailing list [6]
as the most effective and expedient way of exchanging information, answering questions,
and progressing any work.

For specific questions related to a given SRv6-related specification, we encourage
the use of the mailing list of the WG that produced that specification.

OPS Area Directors: Mohamed Boucadair & Mahesh Jethanandani
Routing Area Directors: Gunter Van de Velde, Jim Guichard, & Ketan Talaulikar
INT Area Directors: Éric Vyncke & Erik Kline
BMWG WG Chairs: Giuseppe Fioccola & Sarah Banks
SRV6OPS WG Chairs: Daniel Voyer, Dhruv Dhody, & Weiqiang Cheng
SPRING WG Chairs: Alvaro Retana, Bruno Decraene, &  Joel M. Halpern
OPSAWG WG Chairs: Benoît Claise, Joe Clarke
6MAN WG Chairs: Bob Hinden, Jen Linkova

* [1] https://datatracker.ietf.org/liaison/1983/
* [2] https://datatracker.ietf.org/wg/
* [3] https://datatracker.ietf.org/doc/draft-ietf-spring-srv6-srh-compression/
* [4] https://datatracker.ietf.org/group/bmwg/about/
* [5] https://datatracker.ietf.org/doc/draft-ietf-bmwg-sr-bench-meth/
* [6] https://www.ietf.org/mailman/listinfo/bmwg
