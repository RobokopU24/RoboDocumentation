# RoboDocumentation - HelloRobokop notebooks
Set of Jupyter notebooks demonstrating basic usage of ROBOKOP tools and methods to access ROBOKOP data.  As an example, these use a simple pathway with 3 consecutive nodes, where the initial node is `Buprenorphine` and the terminal node is `Tremor`.

## List of notebooks
- HelloRobokop.ipynb
	- An introductory demonstration of each tool and how to query each of the APIs available
- HelloRobokop_TRAPI.ipynb
	- A demonstration of querying using TRAPI and writing results for comparison
    - Includes querying via automat and Aragorn
- HelloRobokop_TRAPI_multiple_IDs.ipynb
	- A demonstration of querying using TRAPI with multiple input IDs and writing results for comparison
    - Includes querying via automat and Aragorn
- HelloRobokop_Cypher.ipynb
	- A demonstration of querying tools using Cypher and writing results for comparison
    - Includes querying via automat
- HelloRobokop_ExEmPLAR.ipynb
	- Includes a description of the ExEmPLAR UI and the Cypher queries available from that source
    - Includes querying the robokopkg directly
- HelloRobokop_Name_Tools.ipynb
	- A demonstration of the Node Normalizer and Name Resolver tools as shown in `HelloRobokop.ipynb`
- HelloRobokop_Compare.ipynb
    - A demonstration of the compare_results() function that gets the common and exclusive edges between two extracted sets of ROBOKOP query results
    - Includes queries to TRAPI