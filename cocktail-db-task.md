### Task Description: Development of a Cocktail Database and Web Service

#### Overview
Your task is to develop both a database and a web service that provides comprehensive information about cocktails. This project involves extracting data from Wikipedia, structuring it into a database, and then developing a web service to serve this data. The service should allow users to query cocktail details by name and receive structured JSON responses containing history, recipe, ingredients, and an image of the cocktail.

#### Objectives
1. **Data Extraction and Database Creation**:
   - Use a locally-run LLM model, such as Llama3, to scrape and structure data from Wikipedia's list of cocktails (https://en.wikipedia.org/wiki/List_of_cocktails).
   - Utilize retrieval-augmented generation (RAG) to standardize the extraction of data despite the non-uniform entries on Wikipedia.
   - Store the structured data in a local database, with the schema accommodating fields for history, recipe, ingredients (with ratios), and an image URL.

2. **API Development**:
   - Develop an endpoint that receives the name of a cocktail and returns a detailed JSON object with the fields specified above.
   - Ensure the API is robust, with error handling for queries that may refer to cocktails not present in the database.

3. **Implementation Flexibility**:
   - While Python and the oLlama framework are recommended for this project due to their suitability for handling LLM tasks, you are free to use other technologies if you believe they offer significant advantages.

#### Deliverables
1. **Complete Source Code**: All code for the database creation and web service, including any scripts for data extraction and processing, should be submitted via a GitHub repository.
2. **Database File**: Include the generated database file in the repository, ensuring it can be easily integrated with the web service.
3. **Documentation**:
   - **Setup Instructions**: Detailed instructions on how to set up and run both the database and the web service locally.
   - **Usage Examples**: Provide example queries and the corresponding responses to demonstrate how the service functions.
   - **Limitations and Challenges**: Discuss any limitations encountered during data extraction and any discrepancies in the data quality.
   - **Future Improvements**: Propose potential improvements or future features that could enhance the functionality or user experience of the web service.

#### Evaluation Criteria
- **Functionality**: Both the database and web service must meet the requirements and perform as expected.
- **Code Quality**: Code should be clean, well-organized, and include appropriate comments.
- **Documentation Quality**: Documentation should be comprehensive, guiding the user seamlessly through setup, usage, and troubleshooting.
- **Innovative Problem-Solving**: Effective handling of the challenges related to non-standardized data sources and data extraction.

#### Submission Guidelines
Please submit your project by pushing all materials to a designated GitHub repository. Ensure that the repository contains all necessary code files, the database file, and detailed documentation. The repository should be public or accessible to the reviewers with provided access details.
