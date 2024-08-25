<h1 align="center"> NordSec24 - NACT </h1>

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white)

```bash
# In panther/ folder
tmux
python3 panther_cli.py --config nordsec24_config.ini  --debug build_webapp;
python3 panther_cli.py --config nordsec24_config.ini  --debug build_worker;
python3 panther_cli.py --config nordsec24_config.ini  --debug run_tools;
echo "Go to http://panther-webapp/index.html?prot=apt"
```

Result at `panther/panther_worker/app/panther-ivy/protocol-testing/apt/test/nordsec`.

### Useful links

- [Usage](USAGE.md)

- [Installation](INSTALL.md)

- [License](LICENSE)

---

## :book: References

For further reading and context on the topics and methodologies used in this tool, refer to the following articles:

- Crochet, C., Rousseaux, T., Piraux, M., Sambon, J.-F., & Legay, A. (2021). Verifying quic implementations using ivy. In *Proceedings of the 2021 Workshop on Evolution, Performance and Interoperability of QUIC*. [DOI](10.1145/3488660.3493803)

- Crochet, C., & Sambon, J.-F. (2021). Towards verification of QUIC and its extensions. (Master's thesis, UCL - Ecole polytechnique de Louvain). Available at [UCLouvain](http://hdl.handle.net/2078.1/thesis:30559). Keywords: QUIC, Formal Verification, RFC, IETF, Specification, Ivy, Network.


For other useful resources, see the following:

- McMillan, K. L., & Padon, O. (2018). Deductive Verification in Decidable Fragments with Ivy. In A. Podelski (Ed.), *Static Analysis - 25th International Symposium, SAS 2018, Freiburg, Germany, August 29-31, 2018, Proceedings* (pp. 43–55). Springer. [DOI](10.1007/978-3-319-99725-4_4) - [PDF](SAS18.pdf)

- Taube, M., Losa, G., McMillan, K. L., Padon, O., Sagiv, M., Shoham, S., Wilcox, J. R., & Woos, D. (2018). Modularity for decidability of deductive verification with applications to distributed systems. In *Proceedings of the 39th ACM SIGPLAN Conference on Programming Language Design and Implementation, PLDI 2018, Philadelphia, PA, USA, June 18-22, 2018* (pp. 662–677). ACM. [DOI](10.1145/3192366.3192414)

- Padon, O., Hoenicke, J., McMillan, K. L., Podelski, A., Sagiv, M., & Shoham, S. (2018). Temporal Prophecy for Proving Temporal Properties of Infinite-State Systems. In *2018 Formal Methods in Computer Aided Design, FMCAD 2018, Austin, TX, USA, October 30 - November 2, 2018* (pp. 1–11). IEEE. [DOI](10.23919/FMCAD.2018.8603008) - [PDF](FMCAD18.pdf)

- Padon, O., McMillan, K. L., Panda, A., Sagiv, M., & Shoham, S. (2016). Ivy: safety verification by interactive generalization. In *Proceedings of the 37th ACM SIGPLAN Conference on Programming Language Design and Implementation, PLDI 2016, Santa Barbara, CA, USA, June 13-17, 2016* (pp. 614–630). ACM. [DOI](10.1145/2908080.2908118)

- McMillan, K. L. (2016). Modular specification and verification of a cache-coherent interface. In *2016 Formal Methods in Computer-Aided Design, FMCAD 2016, Mountain View, CA, USA, October 3-6, 2016* (pp. 109–116). [DOI](10.1109/FMCAD.2016.7886668)

- McMillan, K. L., & Zuck, L. D. (2019). Formal specification and testing of QUIC. In *Proceedings of ACM Special Interest Group on Data Communication (SIGCOMM’19)*. ACM. Note: to appear. [PDF](SIGCOMM19.pdf)

- [Ivy Documentation](https://microsoft.github.io/ivy/)

- [Ivy GitHub Repository](https://github.com/microsoft/ivy)
