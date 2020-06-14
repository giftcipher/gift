GIFT is a family of two very lightweight block ciphers: GIFT64 and GIFT128. 

# Team
- **[Subhadeep Banik](https://sites.google.com/site/monsieurlelanc)**, EPFL, Switzerland
- **Sumit Kumar Pandey**, Ashoka University, India
- **[Thomas Peyrin](https://sites.google.com/site/thomaspeyrin/)**, Nanyang Technological University, Singapore
- **Yu Sasaki**, NTT, Japan
- **Siang Meng Sim**, DSO National Laboratories, Singapore
- **[Yosuke Todo](https://ysktodo.wordpress.com/)**, NTT, Japan

You can contact us on [giftcipher@googlegroups.com](mailto:giftcipher@googlegroups.com)

# NIST lightweight cryptography competition

GIFT is used as subpcomponent of several [NIST lightweight cryptography competition](https://csrc.nist.gov/Projects/lightweight-cryptography) candidates, notably [GIFT-COFB](https://www.isical.ac.in/~lightweight/COFB/).

# Documentations 

The CHES 2017 paper can be found on the [Springer page](https://link.springer.com/chapter/10.1007/978-3-319-66787-4_16) (conference slides [here](https://ches.iacr.org/2017/slides/ches2017s5t3.pdf)) and the updated and full version of the article is available on [ePrint](https://eprint.iacr.org/2017/622.pdf). You can also find [here](https://eprint.iacr.org/2017/1040.pdf) a work on threshold implementations of GIFT by Gupta et al.


# Implementations

You can find test vectors and reference C implementations for both versions of GIFT on the [GitHub repository of GIFT](https://github.com/giftcipher/gift). 

### Software 

You can find in this [GitHub repository](https://github.com/aadomn/gift) very efficient 8-bit AVR, 32-bit ARM Cortex-M3 and general 32-bit implementations of GIFT and Authenticated encryption GIFT-COFB. 
 
### Hardware 

You can find efficient reference, round-based and fully unrolled hardware implementations of GIFT on [this GitHub repository](https://github.com/qantik/Energy-Analysis-of-Lightweight-AEAD-Circuit). You can also find extremly low-area hardware implementation on [this GitHub repository](https://github.com/qantik/Low-latency-Meets-Low-area-An-Improved-Bit-Sliding-Technique-for-AES-SKINNY-and-GIFT).
