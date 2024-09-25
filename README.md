# **UPO LaTeX Thesis Template**

## Welcome to the **UPO LaTeX Thesis Template** Repository

This repository provides a collaborative, open-source LaTeX template for writing PhD theses at the **Universidad Pablo de Olavide (UPO)**. The goal is to develop and maintain a high-quality template that simplifies the thesis writing process for UPO PhD students, adhering to university guidelines. We invite the academic community to contribute and improve the template, ensuring it remains up-to-date and customizable for everyone.

### Repository Structure

The template is organized in a modular way to simplify usage and maintenance. Each section of your thesis is separated into its own folder or file to facilitate editing.

```
UPO_LaTeX_Thesis_Template/
│
├── 0_Front/                    # Front matter and introductory pages
│   ├── 0_1_cover.tex           # Cover page template
│   ├── 0_2_front_page.tex      # Main title page
│   ├── 0_3_teseo.tex           # TESEO page (for UPO requirements)
│   ├── 0_4_dedication.tex      # Dedication page (optional)
│   ├── 0_5_acknowledgement.tex # Acknowledgements section
│   ├── 0_6_abstract.tex        # Abstract page
│   ├── 0_7_acronyms.tex        # Acronyms list
│   ├── front.tex               # Front matter LaTeX file
│
├── 1_Introduction/             # Introduction chapter
│   └── introduction.tex
│
├── 2_Related_work/             # Related work or literature review chapter
│   └── related_work.tex
│
├── 3_Proposed_method/          # Proposed method chapter
│   └── proposed_method.tex
│
├── 4_Experiments_results/      # Experiments and results chapter
│   └── experiments_and_results.tex
│
├── 5_Discussion_future_lines/  # Discussion and future work chapter
│   └── discussion_and_future_lines.tex
│
├── 6_Conclusion/               # Conclusion chapter
│   └── conclusion.tex
│
├── 7_anexo/                    # Annexes or appendices
│   └── anexo.tex
│
├── figures/                    # Folder to store figures and images
│   ├── faculty_icon.png
│   ├── sample_image.png
│   ├── UPO_icon.png
│   └── (more image files...)
│
├── Style/                      # Style and settings files for the thesis
│   └── settings.tex
│
├── Thesis.tex                  # Main LaTeX file that includes all chapters
├── Thesis_details.tex          # File for thesis-specific details (title, author, etc.)
├── references.bib              # Bibliography file in BibTeX format
│
└── README.md                   # This README file
```

### How to Use the Template

1. **Clone the Repository:**
   Download the template by cloning this repository:
   ```bash
   git clone https://github.com/your-username/UPO_LaTeX_Thesis_Template.git
   ```

2. **Edit Thesis Details:**
   - Open the `Thesis_details.tex` file and fill in your thesis title, author name, advisor details, and other specific information.
   
3. **Write Your Thesis:**
   - The template is structured in chapters with a dedicated folder for each section of your thesis. For example, the `1_Introduction/` folder contains `introduction.tex`, where you can write the introduction chapter. 
   - Include your figures in the `figures/` folder, and manage your bibliography in `references.bib`.

4. **Compile the Document:**
   - To generate the final thesis PDF, compile the main file `Thesis.tex` using your LaTeX editor or the command line:
   ```bash
   pdflatex Thesis.tex
   ```

### Contributing

This repository is **open for collaboration**, and contributions are welcome! Whether you are a LaTeX expert or a student, your input helps improve the template for future UPO PhD students.

#### How to Contribute:
1. **Fork the repository** on GitHub and clone your forked version to your machine.
2. **Make changes** by editing, improving, or adding to the template. Some areas where contributions would be especially helpful include:
   - Adding new formatting options that align with UPO's guidelines.
   - Enhancing documentation and instructions for users.
   - Extending the template with new sections, such as acknowledgments or appendices.
3. **Submit a pull request**: After making your improvements, submit a pull request. We will review it and integrate useful changes into the main repository.

### Areas for Improvement

We are looking for contributions in the following areas:
- **Template Customization**: Improve or add more customizable features for users with different formatting requirements.
- **Bug Fixes**: Fix any issues that arise with compatibility or formatting in specific LaTeX distributions.
- **Documentation**: Enhance instructions for new users, including examples for advanced LaTeX features.
- **Internationalization**: Support for writing theses in multiple languages (e.g., Spanish and English).

### Issues and Support

If you encounter any issues while using the template or have suggestions for improvements, feel free to open an issue in this repository. You can also reach out through the discussion section on GitHub for help or advice.

### License

This project is licensed under the **MIT License**, which allows for free use, distribution, and modification. See the `LICENSE` file for more details.

### Contact

For questions or further information, you can contact the repository maintainers through GitHub.

