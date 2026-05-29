# AI-Project-Starter-Repository
from app.services.llm import ask_llm


def main():
    prompt = "Explain what this project does."
    response = ask_llm(prompt)
    print(response)


if __name__ == "__main__":
    main()
